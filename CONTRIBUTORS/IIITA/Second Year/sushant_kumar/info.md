We should have to follow this as if the commmit is not pushed online yet the we have to follow only two of the strps but if the message is committed online then we have also to force push the value


On the command line, navigate to the repository that contains the commit you want to amend.

step1)Type "git commit --amend" and press Enter...

step2)Use the push --force-with-lease command to force push over the old commit.

step3)this is the command actually "$ git push --force-with-lease origin EXAMPLE-BRANCH"