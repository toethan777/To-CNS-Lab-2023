# Ethan To, Computer and Network Security, 31AUG23
## Provisioning a Virtual Machine
First, I have successfully provisioned an environment for my virtual machine which could be used for hosting a website from a server. As seen below:

![alt text](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW1/Vagrant_html_working.png)



## Configuring the Network

The next thing I did was configuring the network; that way, I could access my created website through my browser.

![alt text](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW1/Website_working.png)

## On the 'Salt' provisioner

It is possible for Vagrant to provision so called 'Salt States.' Salt states use YAML documents which are human readable and used for configuring a system. They describe the current state of a machine which may include installed packages and services that are running.

## File Provisioning

Finally, I have successfully added a file onto my virtual box from my local computer using file provisioning. Here is what the first few lines outputs:

![alt text](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW1/Working_file.png)

### Final note
I had some configuration issues with GIT bash on my computer, so I dragged the first few files in. Everything is OPS normal now.
