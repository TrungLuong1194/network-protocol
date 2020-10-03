# Protocol IP and static routing

## 1. Start virtual machine
```bash
ltabstart -d root_dir/
```
- ex: ltabstart -d net/

## 2. Shutdown vm
```bash
lcrash -d root_dir/
```
- ex: lcrash -d net/

## 3. Show information of network
```bash
ip a
ip l
```

## 4. Test connection using Ping
```bash
ping address
ping address -c numb // Ping with numb packets
```
- ex: ping 192.168.0.1 -c 5

## 5. Display routing table
```bash
ip r
```

## 6. Intercept messages by ARP
```bash
tcpdump -tn -i eth0
```
