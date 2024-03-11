# Botucatu 2024

**Genome assembly by Oxford Nanopore sequencing**

**Session_0**

Session objectives: Install virtual machine and software for the course


**Step 1:**

The virtual machine and tools must be installed before the course starts. Linux and macOS users can use their OS directly.
For Windows users (and others), we suggest installing VirtualBox on your computers (https://www.virtualbox.org).
You may download a pre-built virtual machine here https://www.osboxes.org/ubuntu/ (Username: osboxes; Password: osboxes.org) 
Alternatively, you can follow this guide for a personalized build and virtual machine: https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview or this dead simple guide: https://www.arcserve.com/blog/dead-simple-guide-installing-linux-virtual-machine-windows or watch this video tutorial: https://www.youtube.com/watch?v=hvkJv71PsCs
We propose to download the last stable Ubuntu Version as the Linux OS to be installed on the virtual machine.
**Important: a minimum of 25 GB is required for the virtual hard disk, 8 GB of RAM and to run the course.** 
**The virtual machine should be functional on the first day of the course to avoid losing time.** 

**Step2:**

1_Go to settings -> Keyboard: enter your keyboard type (if not set during installation).  
2_Open Terminal -> Type: sudo apt-get -y install dkms build-essential and enter the password. Type Y.  
3_In the bar above, click on insert CD picture guest addition.  
4_Run VBoxLinuxAdditions.run as sudo.  
5_sudo usermod -a -G vboxsf $USER  
If you want to share files between the computer's OS and the virtual machine, see this tutorial on sharing files: https://medium.com/macoclock/share-folder-between-macos-and-ubuntu-4ce84fb5c1ad

**Step3:**

You need to install Anaconda on your computer (https://www.anaconda.com/products/distribution). Anaconda is an open-source Python distribution, offering a very simple way to install software.
Download the Anaconda installer from the Linux virtual machine (or from Linux or macOS system for these users): 64-Bit (x86) Installer (737 MB) file and run it as follows:
In a Terminal: chmod 755 [Anaconda file]
./[Anaconda file]


**Step4:**

Start Jupyter notebook from a terminal.

Type: jupyter notebook  
Press ENTER.
The web browser should open a new page with the Jupyter default page.
Click on New (with Python as the default language).

Now, Jupyter is functional on your virtual machine.
Go to the Session_0 directory and open session_0_jupyter_notebook_basics.ipynb to learn how to use Jupyter.



