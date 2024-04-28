# Nokia SR OS EVPN-MPLS Lab

| Command | Description |
| --- | --- |
| Description | A lab to demonstrate EVPN-MPLS on Nokia SR OS with containerlab |
| Components | Nokia SR OS, Multitool Alpine Linux |
| Resource requirements |  |
| Topology file | sros-ev-mpls.clab.yml |
| Name | sros-ev-mpls |
| Version information | containerlab:0.27.1, srlinux:22.3.2, vr-sros:22.5.R1, docker-ce:19.03.13 |

![Topology](images/topology.png)


# Tested environment
- SR OS: 23.10.R1

# Configuration
- Topology: Spine-leaf
- Underlay: iBGP with OSPF
- Overlay: EVPN-MPLS
- BUM: Ingress Replication
- Others: BFD, ECMP
