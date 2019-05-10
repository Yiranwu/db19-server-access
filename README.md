# Setting up SSH and VPN

SSH tools support remote connections. Install an SSH tool, for example in Linux:

'sudo apt install openssh-client -y'

VPN is required to connect to the server. You can follow (https://it.umn.edu/downloads-guides-install-anyconnect-vpn-3) to setu p the VPN tool.

Start VPN connection with

'''
server: anyconnect.apexlab.org:4443
username: apexlab
pw: 51apexlabvpn
'''

Start SSH connect with

'ssh db19@172.16.2.235'

pw is also db19.

We have mysql-server, postgresql, java env and ant env correctly configured on the server.

To start mysql, type

'mysql -u db19 -p'

pw is also db19.

Type 'use acmdb', and try anything you like :)