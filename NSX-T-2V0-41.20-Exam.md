# NSX-T 2V0-41.20 Exam
***********************


QUESTION 1  
An NSX administrator is configuring the KVM hypervisor host as a transport node and wants to apply the Failover Order as a NIC teaming policy.
Which profile allows the administrator to configure the NIC Teaming policy as Failover Order?
A. N-VDS/VDS Profile  
B. Transport Node Profile  
C. Host Switch Profile  
D. Uplink Profile  

-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 2    
Which two choices are prerequisites to configure NSX-T on VDS? (Choose two.)  
A. MTU 1500  
B. MTU 1400  
C. vSphere Distributed Switch 6.5  
D. vSphere Distributed Switch 7.0  
E. MTU 1600  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: DE  
QUESTION 3    
Which three steps are required to create an IPsec VPN tunnel? (Choose three.)  
A. Create an IPsec service.  
B. Add a local endpoint.  
C. Configure an IPsec session.  
D. Configure a distributed firewall policy.  
E. Add a logical switch.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: ABC  
QUESTION 4    
An NSX administrator wants to create a Tier-0 Gateway to support equal cost multi-path (ECMP) routing.  
Which failover detection protocol must be used to meet this requirement?
A. Beacon Probing (BP)  
B. Host Standby Router Protocol (HSRP)  
C. Bidirectional Forwarding Detection (BFD)  
D. Virtual Router Redundancy Protocol (VRRP)  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 5    
What are two supported N-VDS modes? (Choose two.)  
A. DPDK Datapath  
B. Overlay Datapath  
C. Secure Datapath  
D. Enhanced Datapath  
E. Standard Datapath  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: DE  
QUESTION 6    
A user is assigned these two roles in NSX Manager:  
LB Admin
Network Engineer
What privileges does this user have in the system?
A. read permissions on all networking services and full access permissions on load balancing features  
B. full access permissions on all networking services and full access permissions on load balancing features  
C. full access permissions on all networking services and read permissions on load balancing features  
D. read permissions on all networking services and read permissions on load balancing features  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: B  
QUESTION 7    
Which CLI command should be executed on a KVM hypervisor to retrieve the VM interface UUID?  
A. virsh dumpxml <VM Name> | grep interfaceid  
B. virsh get-interface <VM Name>  
C. virsh show <VM Name> | grep interfaceid  
D. virsh list-interface <VM Name>  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
QUESTION 8    
Which two choices are use cases for Distributed Intrusion Detection? (Choose two.)  
A. Identify security vulnerabilities in the workloads.  
B. Use agentless antivirus with Guest Introspection.  
C. Quarantine workloads based on vulnerabilities.  
D. Identify risk and reputation of accessed websites.  
E. Gain insight about micro-segmentation traffic flows  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AC  
QUESTION 9    
What needs to be configured on a Tier-0 Gateway to make NSX Edge Services available to a VM on a VLAN-backed logical switch?  
A. Service interface  
B. Loopback Router Port  
C. Downlink interface  
D. VLAN Uplink  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 10    
Which CLI command does an NSX administrator run on the NSX Manager to generate support bundle logs if the NSX UI is inaccessible?  
A. get support-bundle file vcpnv.tgz  
B. set support-bundle file vcpnv.tgz  
C. vm-support  
D. esxcli system syslog config logger set --id=nsxmanager  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
An NSX administrator would like to export syslog events that capture messages related to NSX host   preparation events.
Which message ID (msgid) should be used in the syslog export configuration command as a filter?  
A. SYSTEM  
B. FABRIC  
C. GROUPING  
D. MONITORING  
https://docs.vmware.com/en/VMware-NSX-T-Data-Center/3.2/administration/GUID-CC18C0E3-D076-41AA-8B8C-133650FDC2E7.html  
https://docs.vmware.com/en/VMware-NSX/4.1/administration/GUID-8085C57D-681A-4435-83A3-CB21C98F4A93.html  
set logging-server <hostname-or-ip-address[:port]> proto <proto> level <level> [facility <facility>] [messageid <messageid>] [serverca <filename>] [clientca <filename>] [certificate <filename>] [key <filename>] [structured-data <structured-data>]
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: B  
QUESTION 12    
Which CLI command shows syslog on NSX Manager?  
A. show log manager follow  
B. get log-file auth.log  
C. get log-file syslog  
D. /var/log/sysloq/syslog.log  

https://docs.vmware.com/en/VMware-NSX-T-Data-Center/3.0/administration/GUID-406AF9C3-E8F7-447A-8E3D-92AFB9D5E973.html  
get log-file <auth.log | controller | controller-error | http.log | kern.log | manager.log | node-mgmt.log | policy.log | syslog> [follow]  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 13    
The NSX Control Plane is responsible for which two functions? (Choose two.)  
A. receive and validate configuration from NSX Policy  
B. host API services  
C. propagate topology information  
D. push stateless configurations to forwarding engines  
E. maintain packet-level statistics  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: CD  
QUESTION 14    
A customer is preparing to deploy VMware Kubernetes on an NSX-T Data Center.  
What is the minimum MTU size for the UPLINK profile?
www.vceplus.com - Free Questions & Answers - Online Courses - Convert VCE to PDF - VCEplus.com
A. 1500    
B. 1650  
C. 1550  
D. 1600  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 15    
An NSX administrator has deployed an NSX Edge on a bare-metal server.  
Which command registers the NSX Edge with the NSX Manager?
A. join management-cluster <nsx-cluster-IP> username admin password <admin-password> thumbprint <nsx-manager-thumbprint>  
B. join cluster <nsx-cluster-IP> username root password <root-password> thumbprint <nsx-manager—thumbprint>  
C. join policy-manager <nsx-manager-ip> username root password <root-password> thumbprint <nsx-manager-thumbprint>  
D. join management-plane <nsx-nanager-ip> username admin password <admin-password> thumbprint <nsx-manager-thumbprint>  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
Which NAT t  ype must the NSX-T Data Center administrator create on the Tier-0 or Tier-1 Gateway to allow Web VM to initiate communication with public
networks?  
A. SNAT  
B. Reverse NAT  
C. DNAT  
D. 1:1 NAT  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
QUESTION 17    
How does Traceflow tool identify issues in a network?  
A. Compares intended network state in the control plane with Tunnel End Point (TEP) keepalives in the data plane.  
B. Compares the management plane configuration states containing control plane traffic and error reporting from transport node agents.  
C. Injects synthetic traffic into the data plane and observes the results in the control plane.  
D. Injects ICMP traffic into the data plane and observes the results in the control plane.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 18    
Which statement is true about an alarm in a Suppressed state?  
A. An alarm can be suppressed for a specific duration in days.  
B. An alarm can be suppressed for a specific duration in minutes.  
C. An alarm can be suppressed for a specific duration in seconds.  
D. An alarm can be suppressed for a specific duration in hours.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 19    
An NSX administrator is troubleshooting a connectivity issue with virtual machines running on an ESXi transport node.  
Which feature in the NSX UI shows the mapping between the virtual NIC and the host's physical adapter?
A. Switch Visualization  
B. Port Mirroring  
C. Activity Monitoring  
D. IPFIX  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
QUESTION 20    
Which two logical router components span across all transport nodes? (Choose two.)  
A. DISTRIBUTED_ROUTER_TIER0  
B. SERVICE_ROUTER_TIER0  
C. TIER0_DISTRIBUTED_ROUTER  
D. DISTRIBUTED_ROUTER_TIER1  
E. SERVICE_ROUTER_TIER1  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AD  
Which step must be performed before deploying an   additional NSX Manager from the NSX-T UI?
A. Prepare the ESXi hosts as Transport Nodes.    
B. Configure the Virtual IP of the cluster.  
C. Register vCenter Server as a Compute Manager.  
D. Create an Edge Cluster.  

https://docs.pivotal.io/pks/1-7/nsxt-install-nsx-mgmt-cluster.html  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
What are two valid   options when configuring the scope of a distributed firewall rule? (Choose two.)
A. Segment Port    
B. Group  
C. Segment  
D. DFW  
E. Tier-1 Gateway  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: BD  
QUESTION 23    
Which two commands does an NSX administrator use to check the IP address of the VMkernel port for the GENEVE protocol on the ESXi transport node? (Choose  
two.)
A. esxcfg-nics -1  
B. net-dvs  
C. esxcli network nic list  
D. esxcfg-vmknic -l
E. esxcli network ip interface ipv4 get  

https://kb.vmware.com/s/article/1008127  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: DE  
QUESTION 24    
Which three services are compatible with VRF Lite? (Choose three.)  
A. VPN  
B. Intrusion Detection  
C. NAT  
D. Load Balancer  
E. DHCP  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: BCE  
QUESTION 25    
Which CLI command is used to start the NSX Manager virtual machine in the KVM environment?  
A. virsh start <NSX-Manager-ID>  
B. virsh poweron <nsx-manager-ID>  
C. virsh start <NSX-Manager-Name>  
D. virsh poweron <nsx-manager-name>  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 26    
In a NSX-T Data Center environment, an administrator is observing low throughput and congestion between the Tier-0 Gateway and the upstream physical routers.  
Which two actions could address low throughput and congestion? (Choose two.)
A. Deploy Large size Edge node/s.  
B. Configure ECMP on the Tier-0 gateway.  
C. Configure NAT on the Tier-0 gateway.  
D. Add an additional vNIC to the NSX Edge node.  
E. Configure a Tier-1 gateway and connect it directly to the physical routers.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AB  
QUESTION 27    
Which three steps must be carried out to configure North-South / East-West Network Inspection? (Choose three.)  
A. Service Deployment  
B. Service Insertion  
C. Service Consumption  
D. Service Registration  
E. Service Introspection  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: ACD  
QUESTION 28    
Which statement describes the VMware Virtual Cloud Network Vision?  
A. Virtual Cloud Network connects and protects virtual machines running in KVM environments.  
B. Virtual Cloud Network connects and protects virtual machines running in vSphere environments.  
C. Virtual Cloud Network connects and protects applications, regardless of their physical locations.  
D. Virtual Cloud Network connects and protects applications and data, regardless of their physical locations  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 29    
Which two commands are used to query the arp-table of a logical switch? (Choose two.)  
A. get logical-switch arp-table <logical-switch-uuid>  
B. get logical-switch arp-table <vni>  
C. get logical-switch arp-table  
D. get logical-switch <logical-switch-uuid> arp-table  
E. get logical-switch <vni> arp-table  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: DE  
QUESTION 30    
An NSX administrator has configured a load balancer virtual server on a Tier-1 Gateway.  
In order to advertise the load balancer virtual IP to the Tier-0 Gateway, which route advertisement configuration has to be done on the Tier-1 Gateway? (Choose
two.)
A. Advertise All LB SNAT IP Routes  
B. All Static Routes  
C. Information  
D. Advertise All LB VIP Routes  
E. Advertise All NAT Routes  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AD  
QUESTION 31    
When a stateful service is enabled for the first time on a Tier-0 Gateway, what happens on the NSX Edge node?  
A. SR and DR doesn’t need to be connected to provide any stateful services.  
B. DR is instantiated and automatically connected with SR.  
C. SR is instantiated and automatically connected with DR.  
D. SR and DR is instantiated but requires manual connection.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 32    
Which CLI command on NSX Manager and NSX Edge is used to change NTP settings?  
A. set time-server  
B. get timezone  
C. set ntp-server  
D. set timezone  

https://vdc-download.vmware.com/vmwb-repository/dcr-public/ffedf5e0-6b2d-4aad-87ab-1045cd6e8233/b1529ef2-8250-497a-8cee-20947fba5072/NSX-T%20Command-Line%20Interface%20Reference.html    
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 33    
Which three teaming policy modes are supported by NSX-T Data Center? (Choose three.)  
A. Destination MAC  
B. Load Balanced Source IP  
C. Failover Order  
D. Destination Port  
E. Load Balanced Source MAC  
F. Load Balanced Source  

https://vstellar.com/2020/08/nsx-t-3-0-seriespart-2-uplink-profiles/#:~:text=Using%20named%20teaming%20policy%20we,use%20vSphere%20VDS%20at%20all.&text=2%3A%20Providing%20deterministic%20NSX%2DT,switch%20via%20a%20single%20pNIC  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:   CEF  
QUESTION 34    
An NSX administrator is creating a Tier-1 Gateway configured in Active-Standby High Availability Mode. In the event of node failure, the failover policy should not  
allow the original failed node to become the Active node upon recovery.
Which failover policy meets this requirement?
A. Non-Preemptive  
B. Preemptive  
C. Enable Preemptive  
D. Disable Preemptive  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
QUESTION 35    
Which two choices are solutions of the NSX portfolio (Choose two.)?  
A. vRealize Automation  
B. NSX Distributed IDS/IPS  
C. vRealize Network Insight  
D. Tanzu Kubernetes Grid  
E. NSX Service Mesh  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: BE  
QUESTION 36    
Where are Distributed Firewall logs containing access decisions stored?  
A. NSX API  
B. NSX Edge  
C. NSX Manager  
D. Hypervisor transport node  

https://docs.vmware.com/en/VMware-NSX/4.1/administration/GUID-D57429A1-A0A9-42BE-A299-0C3C3546ABF3.html  
If logging is enabled for firewall rules, you can look at the firewall packet logs to troubleshoot issues. The log file is /var/log/dfwpktlogs.log on ESXi hosts.
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 37    
What are three NSX Manager roles? (Choose three.)  
A. cloud  
B. manager  
C. zookeeper  
D. policy  
E. master  
F. controller  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: BDF  
QUESTION 38    
Which three can an administrator define in a transport node profile? (Choose three.)  
A. Logical Router  
B. Segment Profile  
C. Segment  
D. Uplink Profile  
E. VDS switch configuration  
F. N-VDS switch configuration  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: DEF  
QUESTION 39    
A DevOps user has deployed a Kubernetes Pod in vSphere.  
What does the term ClusterIP represent within NSX-T?
A. Deployment of T1 with NLB service.  
B. Deployment of Distributed Router.  
C. Deployment of Distributed Load Balancing service.  
D. Deployment of T0 and T1  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
QUESTION 40    
How many IPs are required when deploying a highly available NSX Management Cluster with VIP in a production environment?  
A. 5  
B. 6  
C. 3  
D. 4  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
QUESTION 41    
An NSX Administrator has created a segment named WEB-LS from the NSX UI and noticed the segment is not realized on the KVM Transport node.  
What are two possible causes for this issue? (Choose two.)
A. The KVM Transport node has hardware issues and will not realize the WEB-LS Segment.  
B. Since the Compute Manager is disconnected in NSX UI, the WEB-LS segment will not be realized on the KVM Transport Node.  
C. The virtual machines running on the KVM Transport Node are connected to the WEB-LS segment, but are in Powered Off state.  
D. The virtual machines running on the KVM Transport Node are not connected to the VDS.  
E. The virtual machines running on the KVM Transport Node are not connected to the WEB-LS Segment.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: BE  
QUESTION 42    
Which profile must be attached to the ESXi cluster to prepare the host for NSX-T Data Center?  
A. Transport Node Profile  
B. Uplink Profile  
C. Switching Profile  
D. Host Profile  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
  
  


file:///D:/T%C3%A9l%C3%A9chargements/vmware.prep4sure.2v0-4120.pdf.download.2023-may-29.by.curitis.28q.vce.pdf
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  
NEW QUESTION 2    
Which command is used to set the NSX Manager's logging-level to debug mode for troubleshooting?  
A. set service nsx-manager logging-level debug  
B. set service nsx-manager log-level debug  
C. set service manager log-level debug  
D. set service manager logging-level debug  

https://kb.vmware.com/s/article/55868  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
NEW QUESTION 3    
Which three protocols could an NSX administrator use to transfer log messages to a remote log server? (Choose three.)  
A. SSL  
B. HTTPS  
C. TLS  
D. UDP  
E. SSH  
F. TCP  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: CDF  
NEW QUESTION 5    
An NSX administrator is reviewing syslog and notices that Distributed Firewall Rules hit counts are not being logged. What could cause this issue?  
A. Syslog is not configured on the NSX Manager  
B. Distributed Firewall Rule logging is not enabled  
C. Zero Trust Security is not enabled  
D. Syslog is not configured on the ESXi transport node  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: B  
NEW QUESTION 6    
Which log is used to see a failed NSX-T installation of a VIB package on ESXi transport nodes?  
A. /var/l og/host  
B. log  
C. /var/log/vmware/eam/eam.log  
D. /var/log/esxupdate.log  
E. /var/log/syslog.log  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: E  
NEW QUESTION 7    
Which two BGP configuration parameters can be configured in the VRF Lite gateways? (Choose two.)  
A. Route Aggregation  
B. Route Distribution  
C. Graceful Restart  
D. BGP Neighbors  
E. Local AS  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  AD ???????????????????????????????? ou BD  
NEW QUESTION 8    
An NSX administrator is planning to deploy a multi-tier routing topology in their NSX-T Data Center environment to provide north-south connectivity for the VMs.  
Which routing component must be deployed?
A. Tier-1 Gateway  
B. Edge Services Gateway  
C. Tier-0 Gateway  
D. Layer 2 Gateway  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
NEW QUESTION 10    
Which is correct when deploying a NSX Edge in a KVM only environment?  
A. deploy NSX Edge VM with QCOW2 image  
B. deploy NSX Edge VM with ISO image  
C. deploy NSX Edge on a bare-metal server  
D. deploy NSX Edge VM with OVF template  

https://docs.vmware.com/en/VMware-NSX-T-Data-Center/3.2/installation/GUID-11417AA2-5EBC-49C7-8A86-EB94604261A6.html  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
NEW QUESTION 10    
Which component does the hyperbus interface (vmk50) provide network connectivity to?  
A. containers running on ESXi/KVM transport nodes  
B. virtual machines and containers running across transport nodes  
C. virtual machines running on the same hypervisor  
D. virtual machines running in the same segment  

https://cloudbytesecurity.com/2019/11/05/prepare-host-transport-nodes/  
https://kb.vmware.com/s/article/67432?lang=en_US  
https://kb.vmware.com/s/article/67432  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
NEW QUESTION 21    
Which two choices are use cases for Distributed Intrusion Detection? (Choose two.)  
A. Identify security vulnerabilities in the workloads.  
B. Use agentless antivirus with Guest Introspection.  
C. Quarantine workloads based on vulnerabilities.  
D. Identify risk and reputation of accessed websites.  
E. Gain insight about micro-segmentation traffic flows.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AC ???????????  
NEW QUESTION 22    
Which statement Is true regarding the audit user account? (Choose two.)  
A. The admin user must set the password for the audit account to log in to NSX Manager.  
B. The administrator must run the set audit user password <password> command.  
C. The audit user has read-write access to the NSX Manager.  
D. The audit user is disabled by default and must be enabled to log in to the NSX Manager.  
E. The administrator must run the set user audit password <password> command.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: DE  
NEW QUESTION 27    
Which CLI command does an NSX administrator run on the NSX Manager to generate support bundle logs if the NSX UI is inaccessible?  
A. get support-bundle file vcpnv.tgz  
B. set support-bundle file vcpnv.tgz  
C. vm-support  
D. esxcli system syslog config logger set --id=nsxmanager  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
NEW QUESTION 30    
Which CLI command would an administrator use to allow syslog on an ESXi transport node when using the esxcli utility?  
A. esxcli network firewall ruleset -e syslog  
B. esxcli network firewall ruleset set -a -e false  
C. esxcli network firewall ruleset set -r syslog -e true  
D. esxcli network firewall ruleset set -r sysloq -e false  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
NEW QUESTION 35    
Which three steps are required to create an IPsec VPN tunnel? (Choose three.)  
A. Create an IPsec service.  
B. Add a local endpoint.  
C. Configure an IPsec session.  
D. Configure a distributed firewall policy.  
E. Add a logical switch.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: ABC  
NEW QUESTION 37    
Which Network and Security virtualization solution provides network hybridity and mobility?  
A. VMware HCX  
B. VMware Tanzu Service Mesh  
C. NSX Advanced Load Balancer  
D. NSX Intelligence  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
  
  
EXAMTOPIC
-------------------------------------------------> 
An NSX administrator noticed that the nsxcli command times out after 600 secs of idle time. Which CLI command disables the nsxcli time out value on NSX Manager?
A. set cli-timeout 0   
B. set cli-timeout enabled  
C. set cli-timeout disabled  
D. set cli-timeout 1  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
An NSX administrator is configuring the KVM hypervisor host as a transport node and wants to ap  ply the Failover Order as a NIC teaming policy.
Which profile allows the administrator to configure the NIC Teaming policy as Failover Order?  
A. N-VDS/VDS Profile  
B. Transport Node Profile  
C. Host Switch Profile  
D. Uplink Profile  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
Which command i  s used to display the network configuration of the Tunnel Endpoint (TEP) IP on a bare metal transport node?
A. ifconfig    
B. tcpdump  
C. debug  
D. ipconfig  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
An NSX administrator has configured a KVM hyperv  isor as a transport node.
Which kernel module on KVM implements a N-VDS?  
A. openvswitch  
B. etherswitch  
C. nsx-vswitch  
D. dvswitch  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
What are two types of support  ed IPSec VPNs in NSX-T Data Center? (Choose two.)
A. policy-based IPSec VPN    
B. Layer-7 based IPSec VPN  
C. route-based IPSec VPN  
D. Open source based IPSec VPN  
E. SSL based IPSec VPN  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AC  
Question #13    
An NSX administrator has been tasked with deploying a NSX Edge Virtual machine through an ISO image.    
Which virtual network interface card (vNIC) type must be selected while creating the NSX Edge VM allow participation in overlay and VLAN transport zones?
A. e1000  
B. VMXNET2  
C. VMXNET3  
D. Flexible  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: C  
Question #14    
What needs to be configured on a Tier-0 Gateway to make NSX Edge Services available to a VM on a VLAN-backed logical switch?    
A. Service interface  
B. Loopback Router Port  
C. Downlink interface  
D. VLAN Uplink  

https://docs.pivotal.io/pks/1-5/nsxt-install-create-t0.html  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
Question #22    
How is the RouterLink port created between a Tier-1 Gateway and Tier-0 Gateway?    
A. Automatically created when Tier-1 is created.  
B. Manually create a Segment and connect to both Tier-1 and Tier-0 Gateways.  
C. Manually create a Logical Switch and connect to bother Tier-1 and Tier-0 Gateways.  
D. Automatically created when Tier-1 is connected with Tier-0 from NSX UI.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
Question #23    
What is the most restrictive NSX-T built-in role which will allow a user to apply configuration changes on a NSX Edge?    
A. Cloud Service Administrator  
B. Network Engineer  
C. Network Operator  
D. NSX Administrator  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: B   ???????????????????????????????????  
Question #24A customer is preparing to deploy VMware Kub  ernetes on an NSX-T Data Center.  
What is the minimum MTU size for the UPLINK profile?    
A. 1500  
B. 1650  
C. 1550  
D. 1600   
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
Question #25    
Which tool could be used to inspect the path of a packet in the data plane?    
A. Port Connection  
B. Port Mirroring Session  
C. Netflow  
D. Traceflow  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: D  
Question #26    
Which two statements are true about the implementation of multicast in NSX-T Data Center? (Choose two.)    
A. Multicast routing is implemented with PIM Sparse-Mode.  
B. IGMP Snooping is used to populate multicast forwarding tables.  
C. Tier-0 gateways can be the Rendezvous Point.  
D. Multicast is supported in ESXi and KVM transport nodes.  
E. An Edge can be the Rendezvous Point.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: AB  
Question #27    
An NSX administrator has deployed an NSX Edge on a bare-metal server.    
Which command registers the NSX Edge with the NSX Manager?
A. join management-cluster <nsx-cluster-IP> username admin password <admin-password> thumbprint <nsx-manager-thumbprint>  
B. join cluster <nsx-cluster-IP> username root password <root-password> thumbprint <nsx-managerג€"thumbprint>  
C. join policy-manager <nsx-manager-ip> username root password <root-password> thumbprint <nsx-manager-thumbprint>  
D. join management-plane <nsx-nanager-ip> username admin password <admin-password> thumbprint <nsx-manager-thumbprint>  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  D  
Question #28    
Refer to the exhibit.    
IMAGE : https://www.examtopics.com/exams/vmware/2v0-4120/view/7/  
Which NAT type must the NSX-T Data Center administrator create on the Tier-0 or Tier-1 Gateway to allow Web VM to initiate communication with public networks?
A. SNAT  
B. Reverse NAT  
C. DNAT  
D. 1:1 NAT  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  A  
Question #29    
How does Traceflow tool identify issues in a network?    
A. Compares intended network state in the control plane with Tunnel End Point (TEP) keepalives in the data plane.  
B. Compares the management plane configuration states containing control plane traffic and error reporting from transport node agents.  
C. Injects synthetic traffic into the data plane and observes the results in the control plane.  
D. Injects ICMP traffic into the data plane and observes the results in the control plane.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  C  
Question #36    
Which three functions require a Services Router (SR) component on an Edge node? (Choose three.)    
A. Service Insertion  
B. Distributed Routing  
C. Packet Forwarding  
D. Gateway Firewall  
E. Distributed Firewall  
F. Virtual Private Network  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  ADF ??????????????????????????????  
Question #37    
Which NSX CLI command is used to check the GENEVE tunnel status on ESXi transport node?    
A. get host-switch <Host-Switch-Name> tunnels  
B. get transport-node tunnel status  
C. get host-switch <Host-Switch-Name> tunnel status  
D. get transport-node tunnel state  

https://vdc-download.vmware.com/vmwb-repository/dcr-public/cc42e3c1-eb34-4567-a916-147e79798957/8264605c-a5e1-49a8-b603-cc78621eeeab/cli.html#get%20host-switch%20%3Chost-switch-name%3E%20tunnels  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: A  
Question #38    
What are two valid options when configuring the scope of a distributed firewall rule? (Choose two.)    
A. Segment Port  
B. Group  
C. Segment  
D. DFW  
E. Tier-1 Gateway  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  BD  
Question #43    
When deploying east-west network introspection, which Service Virtual Machine (SVM) deployment method achieves the least amount of traffic hairpinning?    
A. Create a secondary vNIC on each quest VM for SVM communication.  
B. Place a partner SVM on each compute cluster node.  
C. Centralize partner SVMs in a service cluster.  
D. Add partner SVMs to an edge cluster.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  B  
  
  




ITEXAM
https://www.itexams.com/exam/2V0-41-20  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  
Question 2    
Which two ports are used by a transport node to communicate with the management and control planes in NSX-T Data Center 3.0? (Choose two.)    
A. 5685  
B. 1235  
C. 5671  
D. 5678  
E. 1234  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  BE  
Question 5    
A company is deploying a NSX-T Data Center micro-segmentation in their vSphere environment to secure a simple application composed of web, app, and database tiers.    
The naming convention will be:
✑ WKS-WEB-SRV-XXX
✑ WKY-APP-SRR-XXX
✑ WKI-DB-SRR-XXX
What is the optimal way to group them in order to enforce security policies from NSX-T Data Center?
A. Create an Ethernet based security policy.  
B. Group all by means of tags membership.  
C. Use Edge as a firewall between tiers.  
D. Do a service insertion to accomplish the task.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  B  
Question 6    
Which to steps must an NSX administrator take to integrate VMware Identity Manager in NSX-T to support role-based access control? (Choose two.)    
A. Create a SAML authentication in VMware Identity Manager using the NSX Manager FQDN.  
B. Add NSX Manager as a Service Provider (SP) in VMware Identity Manager.  
C. Create an OAuth 2.0 client in VMware Identity Manager.  
D. Enter the Identity Provider (IdP) metadata URL in NSX Manager.  
E. Enter the service URL, Client Secret, and SSL thumbprint in NSX Manager.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  CE  
Question 8    
Which TraceFlow traffic type should an NSX administrator use for validating connectivity between App and DB virtual machines that reside on different segments?    
A. Multicast  
B. Anycast  
C. Unicast  
D. Broadcast   
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  C  
Question 9    
When running nsxcli on an ESXi host, which command will show the Replication mode?    
A. get logical-switch <Local-Switch-UUID> status  
B. get logical-switch <Logical-Switch-UUID>  
C. get logical-switches  
D. get logical-switch status  

https://vdc-download.vmware.com/vmwb-repository/dcr-public/cc42e3c1-eb34-4567-a916-147e79798957/8264605c-a5e1-49a8-b603-cc78621eeeab/cli.html#get%20logical-switch%20%3Clogical-switch-id%3E%202  

get logical-switch <logical-switch-id>
get logical-switch <logical-switch-id>
get logical-switch <logical-switch-id> arp-table
get logical-switch <logical-switch-id> arp-table
get logical-switch <logical-switch-id> mac-table
get logical-switch <logical-switch-id> mac-table
get logical-switch <logical-switch-id> nd-table
get logical-switch <logical-switch-id> ports
get logical-switch <logical-switch-id> vtep
get logical-switch <logical-switch-id> vtep-table
get logical-switch <uuid>
get logical-switch <uuid> l2forwarders
get logical-switch <uuid> l2forwarders high-availability history state
get logical-switch <uuid> l2forwarders high-availability state
get logical-switch <uuid> mac-address-table
get logical-switch <uuid> neighbor
get logical-switch <uuid> ports
get logical-switch <uuid> ports
get logical-switch <uuid> ports stats
get logical-switch <uuid> rtep-group-mac-address-table
get logical-switch <uuid> rtep-group-mac-address-table <rtep-group-id>
get logical-switch <uuid> rtep-groups
get logical-switch <uuid> tunnel-ports
get logical-switch <uuid> vtep-table
get logical-switch <vni-or-uuid>
get logical-switch <vni-or-uuid> arp-table
get logical-switch <vni-or-uuid> arp-table remote
get logical-switch <vni-or-uuid> arp-table remote verbose
get logical-switch <vni-or-uuid> arp-table verbose
get logical-switch <vni-or-uuid> mac-table
get logical-switch <vni-or-uuid> mac-table remote
get logical-switch <vni-or-uuid> mac-table remote verbose
get logical-switch <vni-or-uuid> mac-table verbose
get logical-switch <vni-or-uuid> stats
get logical-switch <vni-or-uuid> transport-node-table
get logical-switch <vni-or-uuid> verbose
get logical-switch <vni-or-uuid> vtep
get logical-switch <vni-or-uuid> vtep verbose
get logical-switch port <uuid>

-----------------------------------------------------------------------------------------------------------------------------> Correct Answer: B  
Question 10    
Which profile must be attached to the ESXi cluster to prepare the host for NSX-T Data Center?    
A. Transport Node Profile  
B. Uplink Profile  
C. Switching Profile  
D. Host Profile  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  A  
Question 11    
Which choice is correct when deploying a NSX Edge in a KVM only environment?    
A. deploy NSX Edge VM with OVF template  
B. deploy NSX Edge on a bare-metal server  
C. deploy NSX Edge VM with QCOW2 image  
D. deploy NSX Edge on physical switch  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  B  
Question 12    
Which command is used to change the NSX CLI administrator password?    
A. set user administrator password <old-password> <new-password>  
B. set user admin password <old-password> <new-password>  
C. set user admin password <password> old-password <old-password>  
D. set user administrator password <password> old-password <old-password>  

https://docs.pivotal.io/pks/1-5/nsxt-install-update-password.html  
set user admin password my-new-pwd old-password my-old-pwd
set user admin password-expiration 120
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  C  
Question 13    
Which statement is true regarding the audit user account? (Choose two.)    
A. The admin user must set the password for the audit account to log in to NSX Manager.  
B. The administrator must run the set user audit password <password> command.  
C. The audit user must be created and have its password changed to log into the NSX Manager.  
D. The administrator must run the set audit user password <password> command.  
E. The audit user has read-write access to the NSX Manager.  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  AB  
Question 14    
Where do you configure the VLANs used in VRF Lite? (Choose two.)    
A. uplink interface of the default Tier-0 gateway  
B. uplink trunk segment  
C. downlink interface of the default Tier-0 gateway  
D. uplink interface of the VRF gateway  
E. segment connected to the Tier-1 gateway  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  BD  
Which two statements   are true for a Tier-1 Gateway? (Choose two.)
A. supports ECMP    
B. owned and configured by the Tenant   
C. always configured in active-standby mode   
D. owned and configured by Service Provider  
E. connects to physical networks  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  CE  
Question 21 ( Topic 1 )    
An NSX administrator is using ping to check connectivity between VM1 running on ESXi1 to VM2 running on ESXi2. The ping tests fails. The administrator knows the maximum transmission unit size on the physical switch is 1600.    
Which command does the administrator use to check the VMware kernel ports for tunnel end point communication?
A. esxcli network diag ping -H <destination IP address>  
B. vmkping ++netstack=geneve -d -s 1572 <destination IP address>  
C. vmkping ++netstack=vxlan-d -s 1572 <destination IP address>  
D. esxcli network diag ping -I vmk0 -H <destination IP address>  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  C    ?????????????????????????  
NEW QUESTION 8    
A security administrator needs to configure a firewall rule based on the domain name of a specific application. Which field in a distributed firewall rule does the  
administrator configure?
A. Profile  
B. Source  
C. Service  
D. Policy  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  A  
NEW QUESTION 22    
Which tool could be used to configure BGP on a Tier-0 Gateway?  
A. PowerShell  
B. API  
C. ESX CLI  
D. NSX CLI  

https://vdc-download.vmware.com/vmwb-repository/dcr-public/cc42e3c1-eb34-4567-a916-147e79798957/8264605c-a5e1-49a8-b603-cc78621eeeab/cli.html  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  D  
A customer has a network where BGP has been enabled and the BGP neighbor is confi  gured on the Tier-0 Gateway. A NSX-T Data Center administrator used the get logical-routers command to retrieve this information:
Which two commands must be executed to check BGP neighbor status? (Choose two.)  
A. vrf 3  
B. vrf 1  
C. vrf 4  
D. sa-nsxedge-01(tier1_sr)> get bgp neighbor  
E. sa-nsxedge-01(tier0_sr)> get bgp neighbor  
F. sa-nsxedge-01(tier0_dr)> get bgp neighbor  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  AE  
Which NSX CLI command is used to check the GENEVE   tunnel status on ESXi transport node?
A. get host-switch <Host-Switch-Name> tunnels    
B. get transport-node tunnel status  
C. get host-switch <Host-Switch-Name> tunnel status  
D. get transport-node tunnel state  


https://vdc-download.vmware.com/vmwb-repository/dcr-public/28fdf409-4954-4ada-b9b7-63c2490af81d/aa8109b7-e2e9-4969-8541-eff94a0a2ab5/NSX-T%20Command-Line%20Interface%20Reference.html#get%20host-switch%20%3Chost-switch-name%3E%20tunnels  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:  A  
  
-----------------------------------------------------------------------------------------------------------------------------> Correct Answer:    
  
--  ---------------------------------------------------------------------------------------------------------------------------> Correct Answer:    
  
