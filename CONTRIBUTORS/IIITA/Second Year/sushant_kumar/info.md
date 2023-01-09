We should have to follow this as if the commmit is not pushed online yet the we have to follow only two of the strps but if the message is committed online then we have also to force push the value


On the command line, navigate to the repository that contains the commit you want to amend.

step1)Type "git commit --amend" and press Enter...

step2)Use the push --force-with-lease command to force push over the old commit.

step3)this is the command actually "$ git push --force-with-lease origin EXAMPLE-BRANCH"


# Different Delete task

first i have written information regarding how i will delete my second  commit and for that
i used my command for deleting recently commit that is my second commit

command is "git reset --hard HEAD^"

and in  first commit i have explain it and in that commit i explain the same thing