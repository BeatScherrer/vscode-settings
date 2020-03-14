# vscode-settings
personal vscode user settings

These settings involve:
 - shortcuts
 - cpp settings
 - editor settings
 - color theme

# setup

clone the repo to a common git location:
```
cd
mkdir git && cd git
git clone git@github.com:BeatScherrer/vscode-settings.git
```
remove the current `User` folder after creating a backup:
```
cp -r ~/config/'Code - OSS/User ~/.config/'Code - OSS/User_bk
rm -rf ~/.config/'Code - OSS'/User
```
symlink the `User` folder to the vs-code user settings:
```
ln -s ~/git/vscode-settings/User ~/.config/'Code -OSS'/
```

# Color Theme
I use my own color theme 'gravel-pit' which can be found as a vscode extension or on the following github repo [gravel-pit](git@github.com:BeatScherrer/gravel-pit.git).


# Recommended extensions
TODO