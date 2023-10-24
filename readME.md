# network
# VLSM SUBNETTING /  CLASSLESS SUBNETTING  192.168.10.0
# commands used

# On switch 
>en
>conf t
>ip default-gateway 192.168.10.1
>int vlan 1
>ip address 192.168.1.3 255.255.255.192
>no shut

# On Router
# configure ports as gateway with their respective ip addresses
# Configure static route
>en
>show ip route
>conf t 
# ip route [network ip] [submask] [route ip]
>ip route 192.168.10.64 255.255.255.224 192.168.10.118
>ip route 192.168.10.96 255.255.255.240 192.168.10.118
>ip route 192.168.10.112 255.255.255.252 192.168.10.118


