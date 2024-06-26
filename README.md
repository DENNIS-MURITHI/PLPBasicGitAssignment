# PLPBasicGitAssignment
How to initiate a git repo, and push your work from local machine to github


steps

denmu@DENNIS MINGW64 ~ (master)
$ cd f:/

denmu@DENNIS MINGW64 /f
$ mkdir PLPBasicGitAssignment

denmu@DENNIS MINGW64 /f
$ cd PLPBasicGitAssignment

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment
$ ls

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment
$ git init
Initialized empty Git repository in F:/PLPBasicGitAssignment/.git/

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/DENNIS-MURITHI/PLPBasicGitAssignment.git

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ touch hello.txt

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello.txt

nothing added to commit but untracked files present (use "git add" to track)

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git add hello.txt

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.txt


denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) af3c6f0] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git status
On branch master
nothing to commit, working tree clean

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/DENNIS-MURITHI/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/DENNIS-MURITHI/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

denmu@DENNIS MINGW64 /f/PLPBasicGitAssignment (master)
