# macbook

<img title="macbook"
     alt="Set up a fresh dev MacBook with my personal preferences"
     src="https://user-images.githubusercontent.com/3181349/91672998-5a273f80-eb64-11ea-8fbe-82b02abf137d.jpg"
     width="450">

Set up a fresh dev MacBook with my personal preferences.

Inspiration taken from the following:

- Mathias Bynen's popular config: https://github.com/mathiasbynens/dotfiles
- Thoughtbot's dev-centric script: https://github.com/thoughtbot/laptop
- The legendary Jessie Frazelle: https://github.com/jessfraz
- Defaults-Write: https://www.defaults-write.com/

## Before Starting

This script will attempt to write plist values in 'protected' domains (e.g. `com.apple.universalaccess`). To make this
possible, it is necessary to ensure that the terminal emulator you are using (most likely `Terminal` if running this on
a fresh MacBook) has (temporary) Full Disk Access.

To do this:
1. Go to System Preferences > Security & Privacy > Privacy
1. Select 'Full Disk Access' from the pick list
1. Unlock the settings pane
1. Ensure your terminal emulator is in the list of allowed applications and checked


