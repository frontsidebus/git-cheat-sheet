A lot of these are taken from https://www.freecodecamp.org/news/git-cheat-sheet/ and consolidated in a quick and dirty markdown page. 

# git-cheat-sheet
because I can never remember these commands!


# git configuration commands 

*list git configuration*
```bash
git config -l
```
*set up git username, email, etc*
```bash
git config --global uesr.name "Commander Shepherd"
```

*cache those creds in your local credential store*
```bash
git config --global credential.helper cache
```

# Repo creation/initialization

*initialize a repo*
```bash
git init
```

*add files to your local repo, so they are ready to commit*
```bash
git add foo.bar
git add foo*
git add vini.file vidi.file vici.file
```

*check the status of your local working repo ie: "did I commit yet?"*
```bash
git status
```

*check your commit history*
```bash
git log -p
```

# Checking out, cloning, committing, and other workflow kinda stuff

*clone a repo locally*
```bash
git clone MY_EXCELLENT_REPO_URL
```

*create a branch and check that branch out locally*
```bash
git checkout -b  MY_EXCELLENT_BRANCH_NAME_PROBABLY_WITH_A_JIRA_CARD_NAME
```

*make some commits*
```bashc
git commit -am "I made some sweet commits, check out my sick new code, j/k it's probably a commit because I misspelled something tbh"
```

*push those new commits to your working branch*
```bash
git push
```

*get a specific commit*
```bash
git show COMMIT_HASH_HERE
```

# Some Oh Shit Buttons

*revert a staged commit*
```bash
git reset HEAD this_file_got_fubarred.code
git reset HEAD -p
```

*fix a recent commit with an ammend*
```bash
git commit --amend
```

