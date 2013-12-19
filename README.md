spoof
=====

#####A script for MacOS to change the MAC address and computer name.
=====
###Installation

Download the repository and execute `spoof` from the terminal.

I suggest adding an alias of `spoof` to `/usr/path`, to enable
spoofing by just typing `spoof` in a terminal window.

Adding spoof to `/usr/path`:

	$ sudo ln -s "/---the-location-of-the-spoof-repository---/spoof" "/usr/bin/spoof"
=====
###Usage:
1) Type `spoof` into a terminal window.

2) Enter your password

Your computer's HostName, ComputerName and LocalHostName will be changed to a randomly generated name. This change persists after rebooting your computer.

Your MAC address will be spoofed, including a random, valid vendor identifier. This change will not persist after rebooting.

####Optional Usage:
You can pass a string as an additional argument to spoof, which will set your computer's name:

	$ spoof "MyComputer"

This will spoof the MAC address and permanently change the computer's HostName, ComputerName and LocalHostName to "MyComputer"

The MAC address can be specifically set by passing a second argument:

	$ spoof "MyComputer" "00:15:45:AC:1F:80"

This will set both, the computer name, and the MAC address.

=====
#####Tested on:

Lion, Mountain Lion, Mavericks

=====
I am a freelance software engineer, if this program is useful to you, please consider supporting me with a donation!

<a href='https://pledgie.com/campaigns/22419'><img alt='Click here to lend your support to: Support the software you use! and make a donation at www.pledgie.com !' src='https://github.com/anconaesselmann/ClassesAndTests/raw/master/images/donate.png' border='0' ></a>
