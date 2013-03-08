Wdsconnection
=============

Windows Deployment Services Connection with Drupal 6.0 Module

This Module connects Drupal 6.0 and Ubercart with a working setup of Windows Deployment Services.

Simple straight-forward installation of module, using the standard way of installing modules.

You might want to have configured properly a Windows Deployment Services on your operating Server.

Also along with the WDS Server, you will need: 
a) AD DS Service,
b) a working WAMP Server,
c) DHCP Service, serving computers inside a subnet,
d) PXE boot Service on port 67 from the previously mentioned DHCP Server

This software is part of my thesis, and therefore copyright material of University Of Patras.

Here is the abstract of the whole Project:

"The purpose of this thesis is to research and develop a system for recovering compromised systems.
Initially, there is a review of the errors and different scenarios which occur during the use of a computer. Then, there are developed different
methods and applications in a computer server, which assumes that the status of a computer in the subnet is either infected or damaged. The basic
application that implemented this system is the property all new computers have: the fact that they can start their operating system through a network.
The management system is via a simple browser-side of the "compromised" computer. After providing the necessary parameters for recovering the computer,
the system restarts and boots the system in the new OS that is supplied by the server. The platform implementation of the server operating system is Windows 2008
Server R2 x64 and the website that provides the service for data recovery has been implemented in​PHP and MySQL. The implementation of the server is done
via Microsoft Services and to implement the part of the boot from the network, Windows Deployment Services are used along with the Protocol TFTP
 for the data transfer of the images of the operating systems. The site is running on an Apache server."
