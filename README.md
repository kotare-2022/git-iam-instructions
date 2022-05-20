# git iam

## initialising the shared computer (only done once, already done on campus computers)

```sh
git clone git@github.com:kotare-2022/git-iam-instructions.git

cd git-iam-instructions

git-iam --init https://gist.githubusercontent.com/toolseda/35d090980a3bd8809d471927e8c813e0/raw/

// if no git-iam command found ERROR
nvm install 16
nvm alias default 16
npm i -g git-iam
```

## using git-iam

This script tells the computer who is committing. 
Run the script in the terminal with: 

```sh
git iam github_username
```

Replace 'github_username' with your GitHub username (no quotemarks around it). 
