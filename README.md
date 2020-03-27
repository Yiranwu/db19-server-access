# acmdb connection setup guide
I inherit this guidline from senior ACM students and make some updates.

## Setting up SSH

SSH tools support remote connections. Install an SSH tool, for example in Linux:

`sudo apt install openssh-client -y`

For Windows user, the git bash have already installed an SSH tool that you can use.

## Setting up VPN

VPN is required to connect to the server. You can use "openconnect" as your VPN tool, where installation guide can be easily found on internet.

Start VPN connection with:

```
server: anyconnect.apexlab.org:4443
username: apexlab
pw: 51apexlabvpn
```

## Connecting to the server

Start SSH connection with

`ssh db19@172.16.2.235`

pw is also db19.

We have mysql-server, postgresql, java env and ant env correctly configured on the server.

To start mysql, type

`mysql -u db19 -p`

pw is also db19.

Type `use acmdb`, and try anything you like :)
