# 25OCT23, Ethan To, Computer Network Security

## Exploit research
I have had a Linux desktop for a while now. I believe it is perfect, BUT I have had trouble with its Bluetooth services. After I shut down the computer for a long time, I sometimes have to manually restart Bluetooth more than once. Perhaps it’s the hardware, but I am not too sure. I have searched online for the issue with very little to uncover…
I want to do an exploit dedicated to this issue. It is called the “Linux Kernel 5.4 - 'BleedingTooth' Bluetooth Zero-Click Remote Code Execution.” The target of choice for this exploit is Ubuntu Linux 20.04.1 with a 5.4 Linux kernel.  It is a program compiled in C that takes a Bluetooth MAC address, a source IP address, and a source port address. When the command successfully runs, the attacker should be able to listen to a specific port with Netcat and then run remote commands, all using a Bluetooth connection within the range of the attacker [1]. Though the user could mitigate the risk of this attack by turning off bluetooth, some people find it preferable to use a Bluetooth connection rather than an audio device with an auxiliary cable; then again, I am not sure about the practicality of this attack.

## CVE CWE Information
 
### CVE-2020-12352 Details

There is a Linux service called BlueZ which according to the Arch Linux Wikipedia “provides the Bluetooth protocol stack,” a service in which you can utilize short range wireless interconnection of various devices such as headphones [4]. This CVE deals with improper access control in the BlueZ service which could potentially allow an attacker to access information at a close range [2].

### CVE-2020-12351 Details
This vulnerability is quite similar to the first one. It deals with unauthenticated access to the BlueZ service. The only difference is that if there is improper input validation this could allow an attacker to gain escalation of privileges at a close range [3].


### Sources:

[1] https://www.exploit-db.com/exploits/49754

[2] https://nvd.nist.gov/vuln/detail/CVE-2020-12352

[3] https://nvd.nist.gov/vuln/detail/CVE-2020-12351

[4] https://wiki.archlinux.org/title/Bluetooth
