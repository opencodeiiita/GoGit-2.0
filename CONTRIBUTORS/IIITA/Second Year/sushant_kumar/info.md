
It is a 3 way merge as defintion is down...


The reason it is called a 3-way merge is because the Merge Commit is based on 3 different commits.

The common ancestor of our branches, in this case sir you have added a commit. This commit contains code before we diverge into different branches.

The tip of the Master branch, that is the last commit performed on the Master branch that i have done while mergig my branch-2 to branch-1

The tip of the Feature branch, the last commit performed on the Feature branch that i will do while while merging my branch-1 to your branch-1

To merge the changes from both the branches, Git looks at the three different snapshots - the before snapshot and the after snapshots. Based on these snapshots, Git combines the changes by creating the new commit called the Merge Commit..
=======

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

