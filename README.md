# HelloNIDS
Building a basic NIDS (Network intrusion detection system) with python &amp; scapy.

This is a python script used as the building blocks of the Hello Security NIDS. 

It is pure python and in its public domain form, extremely basic. 

It has limited functions but these functions can and have been built upon such as adding filters to detect more suspicious objects / requests

This script was created for the purpose of sharing with the cybersecurity community and adding to the Hello Security Research Labs roster of tools, wares and services.

This code captures packets on ports 110, 25, and 143 (POP3, SMTP, and IMAP) and checks if the packet payload contains the words "user" or "pass". If it does, the code prints the server IP address and port number, as well as the captured usernames and passwords.
Keep in mind that this is just a basic NIDS building block and there are many more steps and considerations involved in building a comprehensive NIDS. 
