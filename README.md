spoof
=====

#A script for MacOS to change the MAC address and computer name.

###Installation
Download the repository and execute `spoof` from the terminal.
I suggest adding an alias to `spoof` to `/usr/path`, to enable
spoofing by just typing `spoof` in a terminal window.

Adding spoof to `/usr/path`:
	sudo ln -s "/---the-location-of-the-spoof-repository---/spoof/spoof" "/usr/bin/spoof"

###Usage:
Type `spoof` into a terminal window.
Enter your password
Your computer's HostName, ComputerName and LocalHostName will be changed to a randomly generated name. This change persists after rebooting your computer.
Your MAC address will be spoofed, including a random, valid vendor identifier. This change will not persist after rebooting.

You can pass a string as an additional argument to spoof, which will set your computer's name:
$ spoof "MyComputer"
will spoof the MAC address and permanently change the computer's HostName, ComputerName and LocalHostName to "MyComputer"
