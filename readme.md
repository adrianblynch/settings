# Settings

## Bash profile

Create, move to repo, and symlink from repo:

```
touch ~/.bash_profile
mv ~/.bash_profile ~/Dropbox/Code/settings/.bash_profile
ln -s ~/Dropbox/Code/settings/.bash_profile ~/

```

## Sublime user preferences

Move to repo and symlink.

```
mv ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/Preferences.sublime-settings ~/Dropbox/Code/settings/
ln -s ~/Dropbox/Code/settings/Preferences.sublime-settings ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```
