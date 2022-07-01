# vm_ubuntu_webserver

Following tut on Run a web server in a Linux VM with Vagrant [Learning Project] - Tutorial Works (https://www.tutorialworks.com/linux-vm-vagrant/).

Got to use VirtualBox and Vagrant to create a webserver inside a virtual machine, Ubuntu. 
I use vagrant to automate updates, download Apache, config, and move content from the shared folder within the virtual machine to the apache HTML folder. 
After downloading Apache, apt(package manager) create and starts service for Apache. HTTP 200!!!!! 🍇

This vagrant provisioning can make a running webserver with given HTML every time I start a new VM! 👨‍💻🧑‍🎨👨🏼‍🏭

What's more?
1. I struggle a bit with DHCP, I tried to create a private network using DHCP, but it keeps crashing with an existing network. 
Now that I tried to create a private network using static IP, it works!! But it's just a static IP.
Underneath is the source that I found to learn more about DHCP.(not the DHCP config clash thing)🥧
- https://www.youtube.com/watch?v=xR0p_yU9Cdo&t=10s
