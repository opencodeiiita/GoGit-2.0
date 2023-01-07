Ques - How to edit the last commit message in git?
Ans - first make a commit message, make a PR then with the help git command 
      "git commit -m "   " --amend " we can overwrite the previous commit message
      after this when we force push the commit otherwise it will throw an error
      as there was no modification in the repo. This we can edit the last commit message.