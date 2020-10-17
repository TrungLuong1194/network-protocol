- Display IP address
```bash
	ip a
```

- Send ICMP Echo Request messages
```bash
	ping address
	ping address -c 2
```

- Intercept ARP Messages
```bash
	tcpdump -nt
	tcpdump -nt -i eth0
```

- Display router table
```bash
	ip r
```

- Display the addresses of all routers along the route to the specified destination
```bash
	traceroute -n address
```