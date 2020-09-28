# Network Packet Sniffer
Network packet sniffer is designed to capture the packets on a network from a single IP address. 

### Example
`sniff.py -i 192.168.1.20 -o packets.pcap -t 20`
will sniff the packets from the ip address of 192.168.1.20, output to the file "packets.pcap" and listen for 20 seconds.

**Note**: This program is not designed to view the packets, only capture them. In order to view the packets, open the output file in a program like [Wireshark](https://www.wireshark.org/)

## Installation
1. Ensure [Python](https://www.python.org/) is installed and up to date
2. Ensure that git is installed by
    * For Debian-based: `sudo apt-get install git`
    * For Arch-based: `sudo pacman -Syu git`
3. Clone the repo by using `git clone "https://github.com/MatthewMusi/Week-6-Exercise"`
4. Run by navigating to directory of `sniff.py` and entering `sniff.py` followed by any parameters.

# Miscellany
We chose the GNU GPL v3 license. We chose this because we want the program to be open-source and available to everyone but we don't want anyone to make it proprietary. We want the code to always be able to be distributed free of charge.

We chose the contributor covenant code of conduct because we feel it is a high standard of rules for the contributors to follow. A lot of big projects use this code of conduct so we figured that it would work well for us as well.