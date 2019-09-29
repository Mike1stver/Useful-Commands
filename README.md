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

2. Repository Management
- git add -f : Used to add files in .gitignore file.

# Developer experience

1. Basic configurations in VSCode
- https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme , Darker High Contrast
- Fira Code : 
  - Install Fonts
  - "editor.fontFamily": "Fira Code",
  - "editor.fontLigatures": true,
  - Restart VSCode
- VSCode Extensions:
  - Bracket Pair Colorizer
  - Git Lens
  - Auto Rename Tag
  - Color Highlight
  - ES7 React/Redux/GraphQL/React-Native snippets
  - Settingns Sync
 - Emmet is Enabled in VSCode by default, but to be bale to use it in JSX, we need
  - Ctrl + Shift + P : Open User Settings
  - Extensions/Emmet : Edit in settings.json
  - Add
        "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    }
    
