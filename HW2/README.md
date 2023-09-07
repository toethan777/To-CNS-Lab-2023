# Finding Docker Containers
##Nginx and PiHole
I was looking around for different containers for docker. I looked up Nginx because I used it before for hosting a website; it is an open source reverse proxy server, which can utilize several different mediums including HTTPS, POP3, and SMTP. Nginx main focus is high performance and low memory usage. The other container I found was Pi-Hole developed by the company of the same name. It is a network level application used for ad-blocking and anti-internet-tracking. If you install it on a Raspberry Pi or other linux distribution, it is possible to create a ad-blocking server for your own personal network.

## Runnning Arch as a Docker Container
I chose the Arch Linux container developed by Levente Polyak. I have dabbled in Arch several times (my last running Arch computer was destroyed due to a power outage). It is a Linux distribution for being lightweight, but also bleeding edge in open source technology so you have to update it often (or else it would crash and die). You have the options of the latest version (the latest version of Arch), base (for minimal packages to operate Arch), and base-devel (for building and compiling). I put labeled this container attacker-10.9.0.2 as seen in the image below:
! 
