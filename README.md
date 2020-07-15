## What is TorGhost ?
TorGhost is an anonymization script. TorGhost redirects all internet traffic through SOCKS5 tor proxy. DNS requests are also redirected via tor, thus preventing DNSLeak. The scripts also disables unsafe packets exiting the system. Some packets like ping request can compromise your identity.

## How to install ?

`git clone https://github.com/GreyCodeNetwork/TorGhost`

`cd TorGhost`

`chmod +x install.sh`

`./install.sh`


## Usage
Torghost v3.0 usage:

  `-s      --start      Start TorGhost`

  `-r      --switch      Request new tor exit node`

`  -x      --stop      Stop Torghost`

`  -h      --help      Print this help and exit`





