'''

▶ git config --global user.name jdgsb      

~                                                                                                     
▶ git config --global user.email uber.tubers@gmail.com

~                                                                                                     
▶ git config --global user.ui true                    

~                                                                                                     
▶ cd ~/code

~/code                                                                                                
▶ mkdir git_test

~/code                                                                                                
▶ cd git_test

~/code/git_test                                                                                       
▶ git init
Initialized empty Git repository in /home/jd/code/git_test/.git/

~/code/git_test  master ✔                                                                             
▶ touch readme.txt

~/code/git_test  master ✗                                                                          ◒  
▶ open readme.txt
Couldn't get a file descriptor referring to the console

~/code/git_test  master ✗                                                                         ◒  ⍉
▶ cat readme.txt  

~/code/git_test  master ✗                                                                          ◒  
▶ nano readme.txt 

~/code/git_test  master ✗                                                                          ◒  
▶ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.txt

nothing added to commit but untracked files present (use "git add" to track)

~/code/git_test  master ✗                                                                          ◒  
▶ git add readme.txt 

~/code/git_test  master ✗                                                                          ✚  
▶ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   readme.txt


~/code/git_test  master ✗                                                                          ✚  
▶ git commit -m "first commit"
[master (root-commit) 7ca847d] first commit
 1 file changed, 2 insertions(+)
 create mode 100644 readme.txt

~/code/git_test  master ✔                                                                         0m  
▶ nano readme.txt 

~/code/git_test  master ✗                                                                       0m ⚑  
▶ git add .

~/code/git_test  master ✗                                                                       0m ✚  
▶ git commit -m "second commit"
[master 810f2a0] second commit
 1 file changed, 2 insertions(+)

~/code/git_test  master ✔                                                                         0m  
▶ git log


~/code/git_test  master ✔                                                                        1m  ⍉
▶ git checkout -b new-branch
Switched to a new branch 'new-branch'

~/code/git_test  new-branch ✔                                                                    54m  
▶ git status
On branch new-branch
nothing to commit, working directory clean

~/code/git_test  new-branch ✔                                                                    54m  
▶ nano readme.txt 

~/code/git_test  new-branch ✗                                                                  55m ⚑  
▶ git add .

~/code/git_test  new-branch ✗                                                                  55m ✚  
▶ git commit -m "Added a line in a new branch"
[new-branch 87e24de] Added a line in a new branch
 1 file changed, 1 insertion(+)

~/code/git_test  new-branch ✔                                                                     0m  
▶ git checkout master
Switched to branch 'master'

~/code/git_test  master ✔                                                                        56m  
▶ nano readme.txt 

~/code/git_test  master ✔                                                                        56m  
▶ git merge new-branch 
Updating 810f2a0..87e24de
Fast-forward
 readme.txt | 1 +
 1 file changed, 1 insertion(+)

~/code/git_test  master ✔                                                                         0m  
▶ git status
On branch master
nothing to commit, working directory clean

~/code/git_test  master ✔                                                                         0m  
▶ nano readme.txt 

~/code/git_test  master ✔                                                                         1m  
▶ git branch -d new-branch 
Deleted branch new-branch (was 87e24de).

~/code/git_test  master ✔                                                                         1m  
▶ git branch -D unmerged-branch
error: branch 'unmerged-branch' not found.

~/code/git_test  master ✔                                                                        2m  ⍉
▶ nano readme.txt 

~/code/git_test  master ✔                                                                        44m  
▶ nano readme.txt 

~/code/git_test  master ✗                                                                      45m ⚑  
▶ git commit -m "Oops 1"
On branch master
Changes not staged for commit:
	modified:   readme.txt

no changes added to commit

~/code/git_test  master ✗                                                                     45m ⚑  ⍉
▶ git add .

~/code/git_test  master ✗                                                                      46m ✚  
▶ git commit -m "Oops 1"
[master 4b57ca2] Oops 1
 1 file changed, 1 insertion(+)

~/code/git_test  master ✔                                                                         0m  
▶ nano readme.txt       

~/code/git_test  master ✗                                                                       0m ⚑  
▶ git add .

~/code/git_test  master ✗                                                                       0m ✚  
▶ git commit -m "Oops 2"
[master c9c0042] Oops 2
 1 file changed, 1 insertion(+)

~/code/git_test  master ✔                                                                         0m  
▶ nano readme.txt 

~/code/git_test  master ✗                                                                       0m ⚑  
▶ git add .

~/code/git_test  master ✗                                                                       0m ✚  
▶ git commit -m "Oops 3"
[master ae250aa] Oops 3
 1 file changed, 1 insertion(+)

~/code/git_test  master ✔                                                                         0m  
▶ git rebase 
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-rebase(1) for details

    git rebase <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


~/code/git_test  master ✔                                                                        0m  ⍉
▶ git rebase -i HEAD~3
Cannot 'squash' without a previous commit

~/code/git_test  87e24de ✔                                                                      50m  ⍉
▶ 

'''