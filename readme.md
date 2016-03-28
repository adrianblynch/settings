# Settings

## Bash profile

Create, move to repo, and symlink from repo:

```
touch ~/.bash_profile
mv ~/.bash_profile ~/Dropbox/Code/settings/.bash_profile
ln -s ~/Dropbox/Code/settings/.bash_profile ~/

```

## Sublime user preferences and key mappings

Move files to repo and symlink back to Sublime directory:

```
mv ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/Preferences.sublime-settings ~/Dropbox/Code/settings/
ln -s ~/Dropbox/Code/settings/Preferences.sublime-settings ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User

mv ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/Default\ \(OSX\).sublime-keymap ~/Dropbox/Code/settings/
ln -s ~/Dropbox/Code/settings/Default\ \(OSX\).sublime-keymap  ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/Default\ \(OSX\).sublime-keymap
```

## Notes

Creating a symlinked file, you don't have to specify the file name `ln -s /one/file /two/file`. You can leave it as the destination directory `ln -s /one/file /two/`.
