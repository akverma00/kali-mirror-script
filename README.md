# kali-mirror-script

Script to change official Kali repository to mirrors. This helps increase packages update and downloading for some users. Please visit my blog post.

#Requirements
Kali Linux, Python3

#Usage
Run the script in privilege mode, such that sources.list could be edited.

Help
# python3 mirrorscript-v2.py -h
usage: mirrorscript-v2.py [-h] [-v] [-https] [-src]

Kali Mirrorscripts-v2 by IceM4nn automatically select the best kali mirror
server and apply the configuration

optional arguments:
  -h, --help     show this help message and exit
  -v, --verbose  enable verbose output
  -https         use HTTPS in apt transport (default HTTP)
  -src           enable sources packages (default disable)



