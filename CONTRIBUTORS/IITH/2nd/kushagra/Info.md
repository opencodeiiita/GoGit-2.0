Hi, i am Kushagra, sophomore at IITH, and i like to learn new things

**Ques** - What do you really understand from SSH keys in VCS? What are the advantages of using it?

**Ans** :
- So SSH (Secure Shell) key helps us in not requiring us to validate our email/username/password again and again when we try to contribute on github by pushing, etc..
- Also its tough for someone to crack SSH keys as they are encoded using RSA encryption, and one needs both public and private keys to gain access. Public key is uploaded on github, while private key is stored in our desktops and is then we can securely connect to github, they can verify our connection and hence we dont need to repeatedly give username, password and we can work non-abruptly


**Ques** - How to edit the last commit message in git?

**Ans** :
- We could commit the last message in git using `git commit --amend -m "<new_message>"`, moreover if one wants to change commit message which is not the last one, one could use `git rebase -i` (interactive mode) and specify the commits that you want to squash , then it will open the editor where one could use the `reword/edit` option to change the commit message
- If the commit is not pushed to the remote repo, then the above command will do the changes. If the chnages are pushed to the remote repo, then we could force push the commit using `-f` flag to the remote repository.
