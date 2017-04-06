Sublime Text Setup
==================

My Sublime Text 3 Setup

```
cd ~/Library/Application Support/Sublime Text 3/Packages/
git clone https://github.com/sheedy/sublime-text-setup User
```

I also sync this folder to Dropbox using [these steps](https://sublime.wbond.net/docs/syncing#dropbox-osx). Git is really just an added extra backup.

If your Dropbox folder is not in the default location, you'll need to change ``~/Dropbox`` to your location.

- Close Sublime Text
- Open Terminal

## First Machine

On your first machine, use the following instructions.

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
mkdir ~/Dropbox/Sublime
mv User ~/Dropbox/Sublime/
ln -s ~/Dropbox/Sublime/User
```

##Other Machine(s)

On your other machine(s), use the following instructions. These instructions will remove your User/ folder and all contents!

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
rm -r User
ln -s ~/Dropbox/Sublime/User
```

## Settings

The most important settings are in the following files:

- `/Users/mick/Dropbox/Apps/Sublime3/User/SublimeLinter.sublime-settings`
- `/Users/mick/Dropbox/Apps/Sublime3/User/EsFormatter.sublime-settings`
- `/Users/mick/Dropbox/Apps/Sublime3/User/Markdown.sublime-settings`
- `/Users/mick/Dropbox/Apps/Sublime3/User/JsFormat.sublime-settings`
- `/Users/mick/Dropbox/Apps/Sublime3/User/jsfmt.sublime-settings`
- `/Users/mick/Dropbox/Apps/Sublime3/User/JSON.sublime-settings`
- `/Users/mick/Dropbox/Apps/Sublime3/User/JSCS-Formatter.sublime-settings`
- `/Users/mick/dev/.jscsrc`
