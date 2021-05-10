1) Install git - https://git-scm.com/downloads  (do next, next , next on installation options)

2) For zooming git bash screen you can use ctrl + 

3) git => To see all git commands write on bash

4) pwd => Print Working Directory

5) cd => To change directory   example cd /c (change drive), cd css (get into directory css)

6) git config --global user.name "Sandeep"  => This command will configure your name in git, you can verify this with command - git config user.name OR git config --list

7) git config --global user.email "wd.sandeep@gmail.com"  => This command will configure your email in git, you can verify this with command  - git config user.email  OR git config --list

8) git config --global core.editor emacs OR git config --global core.editor vim   => use this command to set editor

9) git status => use this to check status of the git

10) git init => initialize new git repository

11) git add --a , git add -A, git add . => add all files into staging area

12) git add first.txt => add a file into staging area

13) git commit -m "message"  => commit all staging area file with a message

14) git log => To see which commits you have done till now, press q for quit logs

15) git log -p => To see which commits you have done till now with the diffrences(adding,removing), press q for quit logs

16) git log -p -3 => To see which commits you have done till now with the diffrences(adding,removing) with number of commits given with arguments here 3, press q for quit logs

17) git log --stat => This will show in short that what happened in this commit

18) git log --pretty=oneline => This will show logs in one line format

19) git log --pretty=short => This will show logs in short (without detail) (author, message).

20) git log --pretty=full => This will show infromation greater then short parameter (author,commit,message).

21) git log --since=2.days => This will show last two days commits(days/months/years can be used).

22) For more detail on logs go to - https://git-scm.com/docs/git-log

23) rm -rf .git => it will remove .git directory and you will loose all git data and activity, logs etc.

24) git clone https://github.com/tensorflow/tensorflow.git tensorflow  => this will copy all content of tensorflow in your local directory named tensorflow

25) ls => to list content all files and directory

26) git diff => compare working directory to staging area

27) git diff --staged => compare last commit to staged area

28) git commit -a -m "Message..." => this command will directly do the commit by passing the staged command (but it will do this for tracked file)

29) git commit --amend  => This is useful to change last commit.

30) git rm third.txt => this will remove file third.txt and will staged delete file.

31) git mv first.txt first_renamed.txt => This will rename a file and also do staged this activity.

32) git rm -cached publisher.pub => this will untrack this file, it will not remove this file from local.

33) git restore --staged first_renamed.txt => this will unstaged any file (given in parameter)

34) git restore first_renamed.txt => this will restore any file from last committed stage

35) git checkout -- first_file.txt => this will match you current file with the last commit file, you will loose current data.

36) git checkout -f => this will match you all files with last checkout(you will loose your current changes if any)

37) git checkout -b develop => this will a new branch named develop

38) git checkout master => this will be use to switch between branch

39) git branch => this is used to see all branches available in git.

40) git branch -v => this is used to see last commit hash with commit message.

41) git branch --merged => this is used to show all merged branches

42) git branch --no-merged => this is used to show not already merged branches.

43) git branch -d develop => This is used to delete branch. It will show you warning/error if didn't merged it.

44) git branch -D develop => This is used to delete branch without error. (no matter whether branch is merged or not) .

45) git remote add origin git@github.com:wdsandeep/dummy.git => this will help you to add/set path name (here is origin)

46) git remote => this command will show the path name 

47) git remote -v => this will show push and pull url/path

48) To add your computer/laptop to github account - https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

49) git push -u origin master => this command will push your changes commit to github. (he -u parameter tells git to set upstream source for this branch. After this is done, no need to set it again, git push origin master is sufficent.)

50) git push -d origin branch1 => this command will delete branch from remote(github).

51) git config --global alias.st status => this help you to alias in place of long commands, for example after using this command you can write git st, instead of git status

52) git merge newFeature => this command will help you to merge branches.(use vscode for conflict resolution)