
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
