![alt text](https://scontent.fnic3-1.fna.fbcdn.net/v/t1.0-9/19399654_301498383593857_6654125625657238679_n.jpg?oh=37993f8b71f5aa6303cddad595802727&oe=5AE63B26)



by blackhatethicalhacking.com

  GNU nano 2.9.3                                               README.md

# Description-

ARP spoofing allows an attacker to intercept data frames on a network, modify the traffic, or stop all traffic. Often the attack 

Github:
https://github.com/blackhatethicalhacking/antispoof
# Prerequisites -

        -Linux distro
        -Python 2.7.x
        -Aircrack-ng
        -espeak (optional)
        -Network card that supports monitor mode



AntiSpoof can perform active scan as well as passive scans in both defensive and offensive modes.

**Defensive mode** - Defensive mode protects the end user from the spoofer by disconnecting the user's system from the network.
**Offensive mode** - Offensive mode disconnects the user's system from the network and further kicks out the attacker by sending $

**Active Scan** - Use when your system is left idle most of the time. Active scan is most efficient method to protect you system $

**Passive Scan** - Use when your system is busy transferring data through the network. Passive scan is efficient in for constant $

**Help**
```bash
bash ./antispoof.sh -h
```
**Defensive mode with Passive scanning**

```bash
bash ./antispoof.sh -d -p wlan0

```

**Offensive mode with Active scan**
```bash
bash ./antispoof.sh -o -a wlan0
```

**Offensive mode with Passive scan**
```bash

bash ./antispoof.sh -o -p wlan0

bash ./antispoof.sh -o -p wlan0
```

**Reset Network Card**
```bash
bash ./antispoof.sh -r wlan0
```

Reset your network card only when used with active mode or when the network adaptor doesn't work properly. Else you can switch ba$


# Records-

The program creates a log file in the folder /usr/antispoof/ containing the details of the attack such as the attackers mac addre$

One can identify the NIC of the attacker's system with the help of the obtained mac address. The whole program is designed specia$

# Edits-
If you wish to get an audio alert please download **espeak** or **comment out those lines** in the source code.


# Note-

1. I won't suggest using this software over wired connections, especially in offensive mode as it might cause network instability.
2. Use the offensive mode only with the NICs that supports monitor mode.
3. Offensive mode does DOS attack on the ARP-spoofer. Use Offensive mode only after making sure that you have appropriate right(s$



