My Name is Ansh Kothari. I am in second year at IIITA.
My enrollment number is IEC2021006.

Private Repo Link: https://github.com/anshgeez31/Private_Repo_OpenCode

Problem facing: While mkdir we are creating a new folder but when we try to git add . it then there is a message appears which says that working tree is clean that means that no changes were detected when you create a directory.
Reason: In Git, directories exist only implicitly, through their contents. Empty directories have no contents, therefore they don't exist. Or to put it another way: Git is a content tracker. .gitkeep is a dummy file that makes sure that git recognises the empty folder so we can include this in an empty folder for git to easily detect it.
This is edited by Ansh Kothari. Roll No. IEC2021006

Q) What do you really understand from SSH keys in VCS? What are the advantages of using it?

Ans).
SSH creates a routes and all the encrypted data are transferred through it with no security issues. we can securely transmit data files. It is more secured than login id and password which could be hacked.
It is a kind of networking protocol, that digs a secure tunnel between the host and the server. It's a two way channel(Secured Shell) that is meant by the exchange of data, in the form of cryptogenically key(4096 bits) used to encrypt it(by using public key:- Which is accessible to everyone) and decrypt(only by the private key:- which is accessible to only host and the server) so that the info. between them got secured, and pass through secured channel and make it free from hacking or data leakage between them by any malicious effect.
