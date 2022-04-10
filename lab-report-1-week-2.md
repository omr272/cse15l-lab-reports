# Lab Report 1 || Week 2

### Installing Visual Studio Code
 - I went to the VS Code website. I used the installer provided on the website.

 ![vscode](vscode.png)

### Remotely Connecting
- First, I installed OpenSSH.
- Then, I opened up a terminal in vscode and entered: ssh 
> cs15lsp22ahc@ieng6.ucsd.edu

> yes

> my password

- Then I successfully connected, with this being the output:

![remotelyconnecting](remote.png)

### Trying Some Commands

> ls -lat
![lslat](lslat.png)
(Shows directories/files, and info associated with such files/directories)

- Some other useful commands that can be used: (cd, cd ~, ls, cat, cp)

### Moving Files with scp

- I created a file in VScode, and I used scp, followed by the filename, and the email I used to login. I remotely connected, then I used ls to show files, and the file I created was there.

![scp](scp.png)

### Setting an SSH Key

- Locally, I ran the command
> ssh-keygen

- Then I entered the local path for .ssh/id_rsa, and a key was generated
- Then I logged onto the server, copied the keys, and now I can login without the need of a password
![keygenpt1](keygen1.png)
![keygenpt2](keygen2.png)

### Optimizing Remote Running

-I still need practice in this area, as I had trouble with the keygen, so it took extra keystrokes to type in the password. Other than that, I used up arrow to summon commands and ; to run multiple commands on one line. Minus the password, it took me about 10 keystrokes

![optimize](optimize.png)





