# Overview
The purpose of this VM is to provide an environment to learn Junos Automation. All the hard work has been done. This VM is a stripped down version of Ubuntu running a very minimal LXDE and the Perl and Python tools from Juniper's github. All the dependencies for all of the libraries have been resolved. It's ready to start coding!

# Features
* Ubuntu 14.04.01 with LXDE
* Eclipse with SLAX plugin
* JUISE
* JSNAP
* Perl 5.18.2 with perl-netconf
* Python 2.7.6 with python-netconf
* Python Py EZ-NC
* Local copy of Junoscriptorium
* git

# Getting Started
## Download
The VM is hosted on Google Drive as it exceeds the filesize limits of Github. Download it [here](http://goo.gl/hDcHLB).

## Installation
View the [wiki](https://github.com/ntwrkguru/junos-automation-vm/wiki)

# Usage
## Login Credentials
Username: automation
Password: automation
sudo pw: automation

## JSNAP
Junos Snapshot Administrator is installed and accessible from the home directory.
./jsnap

## JUISE
JUISE is installed and can be invoked by running the command 'juise'.

## Junoscriptorium
A copy of the Junoscriptorium is located in the home directory. /home/automation/Junoscriptorium/ To refresh the library copy and paste this in the shell or a terminal window:
`cd ~.source && git pull https://github.com/Juniper/junoscriptorium.git`

# References

* juise
* libslax
* Junos PyEZ
* Junoscriptorium

# Support
Use the [issues tab](https://github.com/ntwrkguru/junos-automation-vm/issues) or reach me on [Twitter](https://twitter.com/ntwrkguru).
