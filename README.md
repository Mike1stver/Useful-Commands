# Useful-Commands
Useful collection of comands i need often

1. Configure git on a new computer:
- git config --global user.name "Your name here"
- git config --global user.email "your_email@example.com"
- git config --global color.ui true
- ssh-keygen -t rsa -C "your_email@example.com"
- cat ~/.ssh/id_rsa.pub

copy the public key to the version controlled git system you use such as GiutHub, Bitbucket, etc.

- git clone --single-branch --branch branchname remote-repo

# Developer experience

1. Basic configurations in VSCode
- https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme , Darker High Contrast
- Fira Code : 
  - Install Fonts
  - "editor.fontFamily": "Fira Code",
  - "editor.fontLigatures": true,
  - Restart VSCode
