# arp-scan

> arp-scan is a command-line tool that uses the ARP protocol to discover and fingerprint IP hosts on the local network.
> More information: <https://www.kali.org/tools/arp-scan/>.

- Scan the local network:

` --localnet`

- Set initial per host timeout to {i} ms, default=500:

` --timeout {i}`

- Set desired outbound bandwidth to {x}, default=256000:

` --bandwidth {x}`

- Use  network  interface {s}:

` --interface {s}`

- Display the packet round-trip time:

` --rtt`

- Send the packets to Ethernet MAC address {m}, The default is the broadcast address ff:ff:ff:ff:ff:ff :

` --destaddr {m}`

- Display verbose progress messages:

` --verbose`
