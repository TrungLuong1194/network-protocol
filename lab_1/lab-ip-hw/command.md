# Protocol IP and static routing

## 1. Start virtual machine
- ltabstart -d root_dir/
ex: ltabstart -d net/

## 2. Shutdown vm
- lcrash -d root_dir/
ex: lcrash -d net/

## 3. Show information of network
- ip a
- ip l

## 4. Test connection using Ping
- ping address
ex: ping 192.168.0.1
- ping address -c numb // Ping with numb packets
ex: ping 192.168.0.1 -c 5
