# gitTutorial

GIT GITHUB NOTES
https://git-scm.com/download/win
Git is a free and open source distributed version control system.

git bush in windows

mkdir gitTutorial
cd gitTutorial // change directory to gitTutorial   // <===
touch index2.html
notepad index2.html
cd ..
code . // opens VSCode

git -v
git help
git help -a
q //for quitting
$ git help --config


$ git config --global user.name Nelzon              // <=== 
$ git config --global user.email nelzonm@gmail.com  // <=== 

git status

echo "# gitTutorial" >> README.md                   // <=== 
$ git init                                          // <===
Initialized empty Git repository in C:/Users/Nelzon/gitTutorial/.git/
 
$ git add gitNOTEs.txt
$ git commit -m "my first commit" // m for message

$ git log
$ git diff // difference between working and staging area
$ git diff --staged

$ git rm --cached gitNOTEs.txt //removed from repository NOT from working area
$ git logged --oneline  

	BRANCH
$ git branch
* main

$ git branch newBranch
$ git checkout newBranch //change to newBranch
Switched to branch 'newBranch'

$ touch anotherFile.txt
$ git add -A                                        // <===
$ git commit -m "Adding a file anotherFile.txt to newBranch"    // <===
$ git status
On branch newBranch
nothing to commit, working tree clean
$ git checkout main
Switched to branch 'main'

$ git branch -D newBranch   // you can delete newBranch from main only
Deleted branch newBranch (was b7f7913).
$ git merge anotherBranch   // you can merge anotherBranch from main only





GITHUB 

$ git remote add origin https://github.com/NelzonMamani/gitTutorial.git     // <===
$ git branch -M main                                                        // <===
$ git push -u origin main                                                   // <===


FROM GITHUB SUPPER IMPORTANT

…or create a new repository on the command line
echo "# gitTutorial" >> README.md
git init
git add README.md                                       // <=== $ git add -A   
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/NelzonMamani/gitTutorial.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/NelzonMamani/gitTutorial.git
git branch -M main
git push -u origin main



git add -A stages all changes
git add . stages new files and modifications, without deletions (on the current directory and its subdirectories).
git add -u stages modifications and deletions, without new files



These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects




Main Porcelain Commands
   add                     Add file contents to the index
   am                      Apply a series of patches from a mailbox
   archive                 Create an archive of files from a named tree
   bisect                  Use binary search to find the commit that introduced a bug
   branch                  List, create, or delete branches
   bundle                  Move objects and refs by archive
   checkout                Switch branches or restore working tree files
   cherry-pick             Apply the changes introduced by some existing commits
   citool                  Graphical alternative to git-commit
   clean                   Remove untracked files from the working tree
   clone                   Clone a repository into a new directory
   commit                  Record changes to the repository
   describe                Give an object a human readable name based on an available ref
   diff                    Show changes between commits, commit and working tree, etc
   fetch                   Download objects and refs from another repository
   format-patch            Prepare patches for e-mail submission
   gc                      Cleanup unnecessary files and optimize the local repository
   gitk                    The Git repository browser
   grep                    Print lines matching a pattern
   gui                     A portable graphical interface to Git
   init                    Create an empty Git repository or reinitialize an existing one
   log                     Show commit logs
   maintenance             Run tasks to optimize Git repository data
   merge                   Join two or more development histories together
   mv                      Move or rename a file, a directory, or a symlink
   notes                   Add or inspect object notes
   pull                    Fetch from and integrate with another repository or a local branch
   push                    Update remote refs along with associated objects
   range-diff              Compare two commit ranges (e.g. two versions of a branch)
   rebase                  Reapply commits on top of another base tip
   reset                   Reset current HEAD to the specified state
   restore                 Restore working tree files
   revert                  Revert some existing commits
   rm                      Remove files from the working tree and from the index
   scalar                  A tool for managing large Git repositories
   shortlog                Summarize 'git log' output
   show                    Show various types of objects
   sparse-checkout         Reduce your working tree to a subset of tracked files
   stash                   Stash the changes in a dirty working directory away
   status                  Show the working tree status
   submodule               Initialize, update or inspect submodules
   switch                  Switch branches
   tag                     Create, list, delete or verify a tag object signed with GPG
   worktree                Manage multiple working trees













# gitTutorial
