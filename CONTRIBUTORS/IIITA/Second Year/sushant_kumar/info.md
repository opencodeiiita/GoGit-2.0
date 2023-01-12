
we know that the fork and PR model is a version of git's own branch-and-merge functionality, in which commits can follow separate paths (called branches) and then be brought back together.

this is called branch and merge

step 1  first we will git checkout branch-2 

then we will commit and push our changes 

step 2. merge it to branch-1 and make a PR for original repo  

# Different delete task

i will give description in first commit and delete my most recent commit that is my second commit using the command 

git reset --hard HEAD^

We should have to follow this as if the commmit is not pushed online yet the we have to follow only two of the strps but if the message is committed online then we have also to force push the value


On the command line, navigate to the repository that contains the commit you want to amend.

step1)Type "git commit --amend" and press Enter...

step2)Use the push --force-with-lease command to force push over the old commit.

step3)this is the command actually "$ git push --force-with-lease origin EXAMPLE-BRANCH"

