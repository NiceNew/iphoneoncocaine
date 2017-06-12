# iphoneoncocaine
A passcode cracking utility for all iOS devices

# sources I used in the project
- libimobiledevice
- afcclient

# How to install
* On a APT based linux:
1. visit http://coffeebreakers.space/apt
2. download install.sh
3. sudo ./install.sh
4. sudo apt-get install libplist
5. sudo apt-get install libimobiledevice
6. connect your iphone
7. idevicepair pair (copy the udid)
8. download iphoneoncocaine source code https://wizardos.stackstorage.com/s/0kDtVqc5qWmnEl1
9. go into the directory with iphoneoncocaine
10. make
11 ./brute.sh [udidhere]
12. An update screen will appear. Manually enter a password an wait 1 second. If nothing happens, use the delete button to and try again.
13. IF YOU ENTER A PASSCODE AND AFTER 1 second delay the screen disappears you have cracked it and the last entered password is the passcode

* On mac:
1. compile libimobiledevice and it's dependencies from source:
the source can be found here: https://github.com/libimobiledevice/libimobiledevice
2. do the same as with an APT based linux starting from step 6
