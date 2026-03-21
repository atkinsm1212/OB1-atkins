## Step 1: Pulling future updates from the original

Whenever you want to sync updates from the original repo:

powershell

`git fetch upstream`
`git merge upstream/main`

Then push the merged updates to your fork:

powershell

`git push origin main`

---

## Step 2: Pushing your own changes

Normal workflow — nothing special here:

powershell

`git add .`
`git commit -m "your message"`
`git push origin main   # goes to your fork only`