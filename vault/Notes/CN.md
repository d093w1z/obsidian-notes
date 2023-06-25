network devices 1
	layer 1:
		hub
		analog modem
	layer 2:
		switch
			app-specific integrated circuit
		wap(wireless access point)
	layer 3:
		multilayer switch 
		router
			software logic

# network devices 2
## Security devices 
### firewall
osi layers: 2,3,4 or 7
blocks via
stateless inspection(rule based)
stateful inspection(only examine state of network)
### ids
passive system
designed to inform
cannot stop/prevent breach
receives copy of traffic
signature based 
anomaly based 
policy based 
### ips
active system 
designed to prevent 
traffic flows through
same standards
makes active response
### vpn
virtual private network 
layer: 2,3 or 7
most at 3
provides encryption at layer 3
# optimization devices 
### lb
content switch 
balances traffic 
### proxy
used to make requests on behalf

## VPN
seen as direct connection

site to site
remote access(host to site)
host to host(ssl vpn)

ipsec protocol
works at layer 3 and above
can be used with AH and ESP
two modes:
transport
tunnel


tls
crypto protocol 
assym crypto 
replaces ssl

ssl
older crypto protocol 
internet transaction
replaced by tls

dhcp
server ----- client
<-discovery
offer->
<-request
ack-> 