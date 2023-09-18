**`git:`** This is the base command for the Git version control system. It is used to interact with Git for various operations like tracking changes, committing code, branching, merging, etc.

**`git config:`** This command is used to configure Git settings. For example, you can set user name, email, preferred text editor, etc.

**`git init:`** This command is used to initialize a new Git repository in the current directory. It creates a new repository with an initial commit.

**`git clone:`** This command is used to create a copy of an existing Git repository. It downloads an existing repository from a remote server and creates a local copy with all the commit history, branches, and files.

**`git add:`** This command is used to stage changes for committing. It prepares files to be included in the next commit. For example, git add filename stages a specific file, and git add . stages all modified files.

**`git commit:`** Records changes made to the files in the repository. It creates a snapshot of the current state of the project.


```
mkdir ichaush3
```
```
cd ichaush3
```
```
git init
```
```
pwd
```
```
ls -larth
```
```
git status
```
```
code . readme.md
```
```
git status
```
```
git add readme.md
```
```
git status
```
```
git commit -m "some comment"
```
```
git status
```
```
code file1.md
```
```
code file2.md
```
```
code file3.md
```
```
git add .
```
```
git log
```
```
git commit -am "new file message" 
```
```
git log
```
