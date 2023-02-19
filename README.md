# superscan
Improved full subnet scan for nmap
<p>
There is now a Linux and Mac version!
<p>
superscan is a add-on to nmap in order to use this you will need to first install nmap
to install nmap for mac run 
<br>
brew install nmap
<br>
OR
<br>
sudo apt install nmap
<p>

Syntax for superscan
<br>
superscan <networkIP/CIDR>
<br>
Example: superscan 192.168.1.0/24
<br>
Example: superscan 172.16.0.0/12
<br>
Example: superscan 10.0.0.0/8
<p>

This addon greatly reduces the time to do an full agressive scan to an entire network.
superscan accomplishes this by running a quick initial scan on all hosts in the network range.
After the initial scan Superscan takes the info from the first round of scans and pipes it into a full agressive scan to give much more information.

















