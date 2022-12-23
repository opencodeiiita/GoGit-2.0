My Name is Ansh Kothari. I am in second year at IIITA.
My enrollment number is IEC2021006.

Private Repo Link: https://github.com/anshgeez31/Private_Repo_OpenCode

Problem facing: While mkdir we are creating a new folder but when we try to git add . it then there is a message appears which says that working tree is clean that means that no changes were detected when you create a directory.
Reason: In Git, directories exist only implicitly, through their contents. Empty directories have no contents, therefore they don't exist. Or to put it another way: Git is a content tracker. .gitkeep is a dummy file that makes sure that git recognises the empty folder so we can include this in an empty folder for git to easily detect it.
