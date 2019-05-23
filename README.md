# macOS config
Steps for configuring a fresh install of macOS.

## Do Not Rearrange Spaces

Open _System Preferences_ and nvaigate to _Mission Control_. Deselect the checkbox labeled _Automatically rearrance Spaces based on most recent use_.

![auto rearrange spaces](images/do-not-rearrange-spaces.png)

## Three Finger Drag

Open _System Preferences_ and navigate to _Accessibility_. Select _Mouse & Trackpad_ on the left side and click the _Trackpad Options..._ button. Select the checkbox for _Enable dragging_ and set the dropdown to _three finger drag_.

![three finger drag](images/three-finger-drag.png)

## Three Finger Look Up

Open _System Preferences_ and navigate to _Trackpad_. Set the dropdown under _Look up & data detectors_ to _Tap with three fingers_.

![three finger look up](images/three-finger-look-up-and-preview.png)

## Display File Name Extensions

Open _Finder_ and open _Preferences_. Navigate to _advanced_ and select the checkbox _Show all filename extensions_.

![file name extensions](images/filename-extensions.png)

## Close Shell on Clean Exit

Open _Terminal_ and open _Preferences_. Select _Profiles_ and then _Shell_. Set the _When the shell exits_ dropdown to be _Close if the shell exited cleanly_.

![](images/close-shell-on-clean-exit.png)

## Default to Plain Text in TextEdit

Open _TextEdit_ and open _Preferences_. Select the radio button for _Plain text_.

![text edit plain text](images/text-edit-plain-text.png)

## Enable Text Message Forwarding

On your phone go to the _Settings_ app and navigate to _Messages_. Select _Text Message Forwarding_ and enable it for the desired computers.

![text message forwarding](images/text-message-forwarding.jpg)

## Homebrew

### Install Homebrew
Run this command
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
or check the [Homebrew site](https://brew.sh/) for the latest install method.

### Install coreutils
```
brew install coreutils
```

## DNS for Work VPN

If there are issues with DNS while on the work VPN then open System Preferences and navigate to Network. Select _Advanced_ and navigate to _DNS_. Set the DNS servers to 8.8.8.8 and 4.4.4.4 as displayed below.

![](images/set-dns-for-work-vpn-1.png)
![](images/set-dns-for-work-vpn-2.png)