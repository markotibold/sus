Sublime User Settings
=====================

Installation
------------

Follow these steps::

    cd /Users/<username>/Library/Application\ Support/Sublime\ Text\ 2/Packages/User 
    git clone https://github.com/markotibold/sus
    ln -s sus/Preferences.sublime-settings Preferences.sublime-settings 


Other
`````

In Lion, holding down a key won't repeat it, but will instead show a popup menu to select between character variations. This doesn't work well with command mode, so you may want to disable it. This can be done via entering this at the terminal::

	defaults write com.sublimetext.2 ApplePressAndHoldEnabled -bool false


Favorite Packages
-----------------

* Djaneiro
* RSTPreview
* SublimeCodeIntel
* SCSS
* SublimeLinter
