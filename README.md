# cookbooks

## Git Pull Request and Review Steps

### Step 1: Create a branch
```
git pull
git checkout -b cb_dev
```

### Step 2: Perform changes in branch

### Step 3: Push the changes to branch
```
git status
git add .
git commit -m "added dev branch"
git push origin cb_dev
```

### Step 4: Open Pull Request tab in the repo in Github portal

### Step 5: Recently pushed branch should be visible with changes highlighted

### Step 6: Review the changes and Create Pull Request

### Step 7: If the changes are fine, merge the branch code into Master branch

The above steps in the background invoking the Webhooks and Events API.
It can be used to post Git status to external portals for tracking 
