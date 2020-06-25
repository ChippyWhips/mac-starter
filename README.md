# 🧑‍💻 mac-starter
The default Mac experience is a bit pants. 

These are the preferences I use after every clean install of MacOS to increase productivity &amp; improve aesthetics.


## Dock

**Remove delay before revealing the dock:**

`defaults write com.apple.Dock autohide-delay -float 0;killall Dock`


**Increase the speed of dock reveal animation:**

`defaults write com.apple.dock autohide-time-modifier -float 0.4;killall Dock`


**Add a spacer tile to the left side of dock:**

`defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock`


**Add a spacer tile to the right side of the dock:**

`defaults write com.apple.dock persistent-others -array-add '{tile-data={}; tile-type="spacer-tile";}' ;killall Dock`

**Keyboard shortcut to show/hide Dock**
`alt` + `d`




---



## Apps

General App settings & tweaks.

**Finder**

Coming soon.

---

## System Preferences

Settings available via System Preferences

**Keyboard**

Coming soon.

**Mouse & Trackpad**

Coming soon.
