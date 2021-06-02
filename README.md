*Git Tutorial*

git add .

git commit -m  "message"

git commit -am "message"

git rm filename

git mv file1 file2

git rm  --cached filename

git diff

git diff --staged

git rm --cached -r foldername

git push

git config --global diff.tool vscode

git config --global difftool.vscode.cmd "code --wait --diff $LOCAL $REMOTE"

git difftool

git log 

git log --oneline

git log --oneline --reverse

git show [> four digit]

// for old git version
git reset

// for lattest git version
git restore --staged

git clean -f