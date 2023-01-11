
Ques - How to edit the last commit message in git?
Ans - first make a commit message, make a PR then with the help git command 
      "git commit -m "   " --amend " we can overwrite the previous commit message
      after this when we force push the commit otherwise it will throw an error
      as there was no modification in the repo. This we can edit the last commit message.

Ques - What do you really understand from SSH keys in VCS? What are the advantages of using it?

Ans - SSH keys replaces username and password while connecting local repo to Github. we can write and access data in repos on github using secure shell protocol (ssh).

Advantages:

SSH makes it faster and secure to transfer files over untrusted network.
we dont have to login using username and password while pushing commits on remote repos.


Ques - Explain the whole process that you will be using to delete that commit.
Ans - I will first make a commit in which i will answer the question . then in the next commit i modify any random file so that i can make another commit on the same branch. after that I will make a PR. and i will use this command "git reset --soft HEAD~1" and remove the last commit, because we are using --soft it will remove the commit but the file that i modified it will still be there in the staging area , i will first unstage it "git reset . OR git reset <file>" then i will remove the changes from working directory "git checkout -- . OR <file>" . after this the HEAD will be at the first commit so I will force push it to the remote repo. and DONE.