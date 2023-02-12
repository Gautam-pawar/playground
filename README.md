# playground
play with code

**
****
*******
********
*********
******Begening******

****1st Task****
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git start
Preparing the exercise environment, hold on...
Exercise master started!
Read the README.md for instructions or view them in browser:
http://gitexercises.fracz.com/e/master
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git start master
Preparing the exercise environment, hold on...
Exercise master started!
Read the README.md for instructions or view them in browser:
http://gitexercises.fracz.com/e/master
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git verify
Verifying the master exercise. Hold on...
Exercise: master        
Status: PASSED        
You can see the easiest known solution and further info at:        
https://gitexercises.fracz.com/e/master/zohg        



****Next task: commit-one-file****        
In order to start, execute: git start next        

See your progress and instructions at:        
https://gitexercises.fracz.com/c/zohg        
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ touch sample.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ nano sample.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git add .
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit -m "first commit"
[master 39eb6c9] first commit
 1 file changed, 2 insertions(+)
 create mode 100644 sample.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git verify
Verifying the master exercise. Hold on...
Exercise: master        
Status: FAILED        
Expected number of commits: 1. Received 2.        


configure.sh  README.md  sample.txt  start.sh  test.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git add start.sh test.txt 
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit - m "2nd commit"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'm' did not match any file(s) known to git
error: pathspec '2nd commit' did not match any file(s) known to git
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git add start.sh
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit -m "first commit"
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git verify
Verifying the master exercise. Hold on...
Exercise: master        
Status: FAILED        
Expected number of commits: 1. Received 2.        

See your progress and instructions at:        
https://gitexercises.fracz.com/c/zohg        
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git start commit-one-file
Preparing the exercise environment, hold on...
Exercise commit-one-file started!
Read the README.md for instructions or view them in browser:
http://gitexercises.fracz.com/e/commit-one-file
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ ls
A.txt  B.txt  README.md  start.sh
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git add A.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit "2nd commit"
error: pathspec '2nd commit' did not match any file(s) known to git
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit -m "second task"
[commit-one-file 50551ba] second task
 1 file changed, 1 insertion(+)
 create mode 100644 A.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git verify
Verifying the commit-one-file exercise. Hold on...
Exercise: commit-one-file        
Status: PASSED        
You can see the easiest known solution and further info at:        
https://gitexercises.fracz.com/e/commit-one-file/zohg        

Next task: commit-one-file-staged        
In order to start, execute: git start next        

See your progress and instructions at:        
https://gitexercises.fracz.com/c/zohg        
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git start commit-one-file-stagedgit status
Invalid exercise: commit-one-file-stagedgit
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ ls
A.txt  B.txt  README.md  start.sh
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git reset
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git status
On branch commit-one-file
Your branch is ahead of 'origin/commit-one-file' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	B.txt

nothing added to commit but untracked files present (use "git add" to track)
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ ls
A.txt  B.txt  README.md  start.sh
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git add A.txt 
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit -m "second commit"
On branch commit-one-file
Your branch is ahead of 'origin/commit-one-file' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	B.txt

nothing added to commit but untracked files present (use "git add" to track)
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git verify
Verifying the commit-one-file exercise. Hold on...
Exercise: commit-one-file        
Status: PASSED        
You can see the easiest known solution and further info at:        
https://gitexercises.fracz.com/e/commit-one-file/zohg        

Next task: commit-one-file-staged        
In order to start, execute: git start next        

See your progress and instructions at:        
https://gitexercises.fracz.com/c/zohg        
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git start commit-one-file-staged
Preparing the exercise environment, hold on...
Exercise commit-one-file-staged started!
Read the README.md for instructions or view them in browser:
http://gitexercises.fracz.com/e/commit-one-file-staged
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git reset
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git status
On branch commit-one-file-staged
Your branch is up to date with 'origin/commit-one-file-staged'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	A.txt
	B.txt

nothing added to commit but untracked files present (use "git add" to track)
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git add A.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git commit -m "3rd task"
[commit-one-file-staged 4267263] 3rd task
 1 file changed, 1 insertion(+)
 create mode 100644 A.txt
gautam@gautam-Lenovo-IdeaPad-S510p:~/exercises$ git verify
Verifying the commit-one-file-staged exercise. Hold on...
Exercise: commit-one-file-staged        
Status: PASSED        
You can see the easiest known solution and further info at:        
https://gitexercises.fracz.com/e/commit-one-file-staged/zohg        

