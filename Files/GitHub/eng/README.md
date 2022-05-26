# GitHub

## Generate Key on Computer

```bash
ssh-keygen
```

Then provide a name for the key or just hit enter. Then press enter to not enter a password.

The default location will be shown in the terminal.

### Show public SSH key

```bash
cat keyName.pub
```

Copy the contents of the pub key ‘keyName.pub’

### Configure SSH key on computer

```bash
eval `ssh-agent`
ssh-add keyName
```

## Register SSH Keys in the GitHub

GitHub → settings → SSH and GPG keys → New SSH key

Paste SSH key in the GitHub

## Connect folder with GitHub

```bash
git remote add origin repositoryLink
```

### Check branch name

```bash
git branch
```

### Delete branch

```bash
git push origin --delete branchName
```

### Push files to GitHub

```bash
git push origin branchName
```

### Pull files from GitHub

```bash
git pull origin branchName
```

### Clone repository

```bash
git clone repositoryLink
```
