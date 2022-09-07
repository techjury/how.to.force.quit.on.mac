# how to force quit on mac

[![how to force quit on mac](gett-stateed.png)](https://icncomputer.com/how-to-force-quit-on-mac/)

Macs aren't infallible, and at some point during your time using them you'll come across a situation in macOS where an app has become unresponsive, leaving you without access to its contents and functions, and only a continually revolving beachball for your troubles.

If the beachball stays on the screen for more than a few minutes and you can't interact with the app's interface, this usually indicates the app in question has crashed, which means it's time to force quit it and restart the app to see if you can pick up where you left off in the hope it won't crash again. Read on to learn how.


## How to Force Quit An App

### Method 1

If the app is acting up, hold down the Option key and right-click its icon in the Dock to reveal a Force Quit action in the popup menu.

### Method 2

_There's a second option for quitting an unresponsive app, and it may be one of the more intuitive solutions._

* Click on the Apple logo in the menu bar.
* Select the "Force Quit" option.
* Click the app that you want to quit. Unresponsive apps will have a "Not Responding" designation next to them.
* After selecting the offending app, click on Force Quit to shut it down.

_Alternatively, you can open the Force Quit applications interface by pressing Command + Option + Escape all at once._

### Method 3

_You can also force quit misbehaving Mac apps using Activity Monitor. You can find it in the /Applications/Utilities folder._

_The main window lists all the apps and processes currently running on your Mac. You'll notice the order jumps around a lot. That's because you're seeing the list being updated every five seconds to show changes in individual app usage statistics._

* Under the Process Name list, select the app or process you want to quit. To make finding the culprit easier, click Process Name in the column header to sort them alphabetically, or use the Search field in the top-right corner of the window to find the app or process. Note that an unresponsive process is labelled with (Not Responding).
* Make sure the app or process is highlighted, then click the Quit (X) button in the top-left corner of the Activity Monitor window.
* Select Quit (this is the same as choosing File -> Quit within an app) or Force Quit, which quits the process immediately.


## Force quit with keyboard shortcuts

**_If your application is not responding, do the following:_**

* Press and hold the following keys: Command + Option + Esc
* Choose the application you want to quit in the **“Force Quick Application”** dialogue box.
* Click **“Force Quit“**.

## Force quit via Terminal

**_Alternatively, you can quit an application using shell command via Terminal._**

* Launch Spotlight Search with Command + Spacebar and search for Terminal. Hit Enter.
* In Terminal, type ps -ax then Enter. This will give you a list of all running process on your Mac along with other details like its respective PID number, elapsed running time, process name and process location.
* To kill (force quit) a specific application, look for its name and note down the PID number.
* Type the following command in Terminal: kill <PID number>
