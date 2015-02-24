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
The VM is hosted on Google Drive to take advantage of Google's global CDN for faster downloads. Download it here.

## Installation
View the [wiki]
### Common to all desktop applications
1. Download the [ZIP file](http://goo.gl/hDcHLB)
1. Extract the ZIP somewhere you will remember

### VMWare Player
_You can download VMWare Player free of charge [here](https://my.vmware.com/web/vmware/downloads)._
1. Start VMWare Player
1. Click "Open a Virtual Machine" and follow the wizard selecting the AutomationVM.vmx file extracted
1. Once installed, click "Play virtual machine"

### VMWare Fusion (Mac)
1. Start Fusion
1. From the Fusion menu bar, click File > Open (or Open and Run).
1. Browse to the location of the AutomationVM.VMX file and click Open.

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
juise
libslax
Junos PyEZ
Junoscriptorium

# Support
Use the [issues tab](https://github.com/ntwrkguru/junos-automation-vm/issues) or reach me on [Twitter](https://twitter.com/ntwrkguru).
