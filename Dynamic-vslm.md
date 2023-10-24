
# Dynamic routing VSLM : CLASSFUL (RIP )
# On Router
# configure ports as gateway with their respective ip addresses and submask
# Configure RIP
>en
>show ip route
>conf t
>router rip
>version 2
# ADD all network thats not available
>network 10.0.0.0