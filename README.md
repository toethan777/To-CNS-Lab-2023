# To-CNS-Lab-2023

Welcome! This is Ethan To's repository for Computer and Network Security Lab.

*I chose to install the Notepad++ editor.

*I was not able to get my personal Linux Desktop to run Vagrant due to VPN issues, and it simply was not useful for lab purposes...
BUT IF I WERE TO it would be quite simple.

I use Manjaro Linux which uses the pacman repository, which is pretty hefty in software packages. I simply ran 'sudo pacman -S vagrant' to install Vagrant.
I also tried a virtual machine of Debian, but it would be redundant to put a virtual machine inside a virtual machine...anyways, 'sudo apt-get install vagrant' to install Vagrant on Debian.

Here's how I would go about creating a binaries for my Virtual Boxes in Linux:
1) For Linux, I would make a directory in root for multiple boxes 'mkdir VBoxes,' and I would go into that folder using 'cd VBoxes'
2) I would create and enter a folder for my desired virtual box using the step above (named 'debianbullseye64' for the purpose of this demostration). We are now in ./VBoxes/debianbullseye64
3) To get the box I want, I would type the command 'vagrant box add debian/bullseye64'
4) Then I would initialize it by typing 'vagrant init debian/bullseye64'. Now we have created a Vagrantfile for our virtual box

If I wanted to go further, I would type 'vagrant up' to start the machine and 'vagrant ssh' to enter. If I was done, I type 'exit' in the virtual box command line and 'vagrant destroy' to terminate the machine.

*For Windows in particular, I have opened GitBash into 'C:\Virtual Machines\DebianVagrant' and did steps 2-4.
