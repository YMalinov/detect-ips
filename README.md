Detect-IPs
==========

A simple BASH script, made to detect which hosts are "up" in a local network by pinging them and outputs their IPs on the screen. You can use the flag "-a" to use arping, instead of regular ping but keep in mind you'll need sudo privileges for it.

Prerequisites:
  iputils (I'm currently not using Thomas Habets' version of arping)

Usage example:

detectips -s 2 -e 254 -r 192.168.1 # will check all IPs from 192.168.1.2 to 192.168.1.254
