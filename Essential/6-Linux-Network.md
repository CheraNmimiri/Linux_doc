### Linux and Network

#### /etc/resolv.conf
- Contains DNS server information.
- Resolving IP addresses to domain names or domain names to IP addresses.

#### ifconfig
- Network interface configuration command.
- Functions:
  - View information.
  - Set configuration (IP address, subnet, default gateway, enable/disable).
  - Show disabled or offline network interfaces: `ifconfig -a`
  - Disable a network interface: `sudo ifconfig [device-name] down`
  - Enable a network interface: `sudo ifconfig [device-name] up`
  - Set IP address on a device: `sudo ifconfig [device-name] [ip-address] netmask 255.255.255.0`

#### route
- Displays the routing table.

#### dig
- Shows DNS information and records.

#### ping
- Sends ICMP ECHO_REQUEST packets to network hosts.
- Usage: `ping [ip-or-website-name]`
  
#### Interface Naming Conventions
- `eth`: Ethernet
- `wlan`: Wireless

These commands and files are essential for configuring and managing network connections in Linux systems.

#### For kill a process on a x port
'sudo fuser -k xxxx/tcp'

