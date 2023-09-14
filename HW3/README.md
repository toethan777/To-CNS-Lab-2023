# Ethan To, CNS, 13SEP23:  SCAP Fun!!!
## Red Hat Linux 8 FUN!!!
After having no luck with Oracle Linux 8 (some problem with finding repositories) and RHEL 9 (after figuring out that the SCC is incompatable with RHEL 9), I have chosen RHEL 8 in a virtual machine. It works! I just had to add my local user as a sudoer file and register my Red Hat account to the virtual machine running in VMWare.
## SCC Tool installation
So, to install the SCC tool, I first used the `wget` command to get the zip file as seen here: 

`wget https://dl.dod.cyber.mil/wp-content/uploads/stigs/zip/scc-5.7.2_rhel8_oracle-linux8_x86_64_bundle.zip`

Next, I use the yum repository to get the unzip tool:

`sudo yum install unzip` 

and unzip the zip file: 

`unzip scc-5.7.2_rhel8_oracle-linux8_x86_64_bundle.zip`

finally, I extract the tar file so I can run `./cscc`:

`tar -xf scc-5.7.2_rhel8_x86_64.tar.gz`

Now, we can run the SCC for RHEL 8!

## Results of the SCC Scan

Note: yes, I did this in VMWare, but as of 13SEP23 @2100, VMware shut me out of my RHEL 8 VM and deleted all of the files for it...

...I will talk about this later, but for purposes of showing my scan running, I have a temporary image of me doing it in Vagrant:

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW3/Screenshot%202023-09-13%20213842.png)


Thanking the lord, I also have a saved zip file of my scan results before my RHEL 8 VM exploded. So, we can take a look at the results right now:

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW3/Screenshot%202023-09-13%20222616.png)

The overall score was 35.5%, 82 passes and 149 fails, 21 CAT I's. It appears like we have some work to do!
