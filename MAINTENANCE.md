## MAINTENANCE 
This project is a fork of [bbatsov/rails-style-guide](https://github.com/bbatsov/rails-style-guide)

### Setup original probject as remote
```bash
# add github repo as remote
git remote add bbatsov https://github.com/bbatsov/rails-style-guide.git 

# verify remotes
git remote -v
```

### Merge bbatsov/rails-style-guide
```bash
git fetch bbatsov

# review changes 
git log --no-merges bbatsov/master ^master # '^' needs to be escaped on zsh

# merge them
git checkout master
git merge bbatsov/master
```

