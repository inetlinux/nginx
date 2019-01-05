DNAT

    iptables -t nat -A PREROUTING -p tcp -i eth0 --dport 80 -j DNAT --to-destination 10.1.0.2-10.1.0.4
