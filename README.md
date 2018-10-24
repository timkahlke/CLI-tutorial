# CLI-tutorial
This repository provides a virtual linux environment and practicals to get used to the basic usage of a command-line interface on unix-like operating systems such as linux distributions and Mac-terminal.

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/AdvancedTwigTec.svg?style=social&label=Follow%20%40AdvancedTwigTec)](https://twitter.com/AdvancedTwigTec)

### Install the program VirtualBox on your computer. 

Installation instructions for Windows and MAC OSX can be found in the VirtualBox folder (MS Word document) or as videos in the videos folder of this repository: VB_WIN_INSTALL.mov for Windows computers, VB_OSX_INSTALL.mov for Mac computers. These files can be downloaded and opened with most common media players

### Start the exercise

1. Download the cli-tutorial.zip and the CLI-Tutorial.pdf.
2. Unzip the cli-tutorial.zip and add it to VirtualBox. A How-To video (StartExercise.mov) is also available in the videos folder of this repository.
3. Read the Cli-Tutorial.pdf for a quick introduction to command-line usage and follow the instructions to complete the tutorial.

Good luck and have fun.

## Trouble-shooting

### Disable VirtualBox USB controller 
If the virtual machine does not boot up properly try to deactivate USB driver support. 
1. Stop the VM
2. In Virtualbox on the left side of the menu right-click the VM and choose "Settings"
3. Disable the USB controller under "Ports / USB"


### Enable Virtualisation
Some windows computers do not allow virtualisation unless specifically enabled in the UEFI-Bios. For ways to enable virtualisation please ask Dr. Google about your specific bios/computer.

### VM does not start up again
If you don't finish the exercise and isntead shut the VM down the VM might not start up again properly. In this case please remove the VM from Virtualbox (right-click remove) and add the file again.
