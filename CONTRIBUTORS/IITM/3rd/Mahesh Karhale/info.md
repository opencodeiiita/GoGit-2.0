Hello I am Mahesh, third year from IIT Madras. I am very enthuastic about web development as well as competitive programming. I am learning javascript and nodejs. I am lil inclined towards design too!

Private repo link - https://github.com/MaheshKarhale2111/Repo_for_opencode-

What do you really understand from SSH keys in VCS? What are the advantages of using it?

GitHub ssh keys are nothing but another way of authentication, slightly different from traditional mode of authentication that is username and password. Using ssh keys gives you advantage of push and fetch data without having to authorize your github credentials everytime you push or fetch plus it comes with additional security. 
Ssh keys are generated in pair- public and private, while public key is given to github and private key remains in system. Whenever authentication operation is required , the private key and public key in github try to communicate and set up authentication, kind of handshake. If matched then opertion proceed further. 
