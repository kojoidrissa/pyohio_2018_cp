## PyOhio 2018 *Welcome to CircuitPython* Tutorial
Participants are expected to follow the setup instructions and have their machines ready before
the tutorial at 12:45pm Sunday, 29 July 2018. Be aware that fully testing setup requires access
to the hardware that will be used during the tutorial. I will be available during the day on
Saturday 28 July 2018 with the necessary hardware. Please contact me via Discord or Twitter
(@kattni) or via email (kattni@adafruit.com) to find me before the tutorial to verify that setup
was successful. 

## Setup
For this tutorial, participants will want to install Mu editor.

Mu 1.0 was released on 20 July 2018. If you installed Mu before this, please update to the most
recent version.

## To install Mu editor on Mac or Windows:
Windows users may install Mu from [here](https://codewith.mu/en/download).

Mac users may install Mu from [here](https://codewith.mu/en/download).

## To install Mu editor on Linux x86:
Linux users must be running Python 3.6 or newer. Install by running `sudo apt install python3`.
Then, install `pip3` by running `sudo apt install python3-pip`.

Next, create a virtual environment: `python3.6 -m venv pyohiocp`. Follow the instructions to
install `venv` if it is not already installed. To activate the virtual environment, run
`source ~/pyohiocp/bin/activate`. Once inside the virtual environment `(pyohiocp)`, install Mu
by running `pip3 install mu-editor`.

Linux users must add their user to the `dialout` group to access the serial console output. From
the command line, run `nano /etc/group`. Find the line with `dialout:` and add your user to the
end of the line, after a comma with no space, i.e. `dialout:foo,your_user`. Then, log out of the
user and log back in for the change to take affect.

## Running Mu editor
To run Mu on Windows, double-click the icon.

To run Mu on Mac, double-click the icon in the Applications folder.

To run Mu on Linux, from inside the virtual environment, type `python3 -m mu` into the
command line.

## Inside Mu editor
Once Mu is opened, it will present a list of options. For this tutorial, choose "Adafruit
CircuitPython".

If there is no CircuitPython compatible board plugged in when the editor is opened, there will
be a dialog box that starts with "Could not find an attached Adafruit CircuitPython device".
This is normal.

## Code for Tutorial
This repo contains all the code used in the tutorial. To access it during the tutorial,
participants can view it on the web, and copy and paste as they follow along. They may wish to
have the files available locally. To do this, install `git` and clone the repo to your machine
using `git clone https://github.com/kattni/pyohio_2018_cp` to create a directory containing the
contents of the repo.

If you choose to clone the repo locally, please do a `git pull` on this cloned repository either
*in the evening of Saturday July 28 or in the morning of Sunday July 29*.