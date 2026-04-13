# Full stack network diagnostics
## Tools and Commands 
.IP Discovery-ip addr
.DNS Resolution-dig (standard and specific DNS server queries)
.Connectivity- ping (Latency testing) and traceroute (path analysis) 
.Port Testing- nc -zv (firewall/security group verification) 
.Application Response -curl -I (status code inspection) 
## Lab Results
-Confirmed google.com resolves to {INSERT IP}
-Average latency to google: {INSERT MS} ms.
-Local Nginx verified as litsening on port 80
-Successfully identified that port 443 is open on remote targets while port 22 is restricted.
