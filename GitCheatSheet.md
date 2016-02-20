
# Helpful when working with Git

### Download Git Bash
```
http://git-scm.com/
```
Git-2.7.1.2-64-bit.exe


### Create SSH key
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
Will create a pubic and a private ssh key somewhere here:
* /Users/you/.ssh/id_rsa
* /Users/you/.ssh/id_rsa.pub

### Copy file content to clipboard
```
CLIP < /Users/you/.ssh/id_rsa.pub
```

### Store your credentials permanently. 
```
git config --global credential.helper wincred
```
Git bash will not ask for your credentials when pushing to Github.
