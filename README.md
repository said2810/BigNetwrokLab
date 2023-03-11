# BigNetwrokLab
Network lab:
  - Each PC is in a separate VLAN(2,3,4,5)
  - MultiLayer Switch-1 (Core 1) root to vlan 2,4
  - MultiLayer Switch-2 (Core 2) root to vlan 3,5
  - Using HSPR between the two core switches
  - Switch-1 (Core 1) IPs will be *.2
  - Switch-2 (Core 2) IPs will be *.3
  - All virtual IPs will be *.1
  - ALL PCs will be *.10
  - All uplink from distribution to Core are forwarding per specific VLAN
TARGET:
  - Is to make all PCs transfere packets to each within previous configuration

