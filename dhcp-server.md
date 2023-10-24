# DHCP SERVER 
# On Router (give it a static ip)
>en
>conf t
>int fa0/0
>ip address 192.168.10.1 255.255.255.0
>no shut


# on the Server provide ip for it 192.168.10.2  
# then move to the services section 
# locate DHCP then configure