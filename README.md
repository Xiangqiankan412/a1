
# Satellite Network DDoS Attack Dataset


## Dataset Description

- The dataset contains 17-dimensional unlabeled traffic features and 84-dimensional labeled traffic features. The traffic feature files include botnet, application layer, network layer, low-rate and DRDoS attack traffic, and normal traffic. Specifically, there are four types of botnet attacks (Ares, BYOB, Mirai, and IRC-Botnet), four types of application-layer DDoS attacks (HTTP-Flood, HTTP-Post, HTTP-Get, and CC), five types of DRDoS attacks (NTP, SSDP, Chargen, Memcached, and SNMP), three types of network-layer DDoS attacks (UDP, SYN, and ACK), and four types of low-rate DDoS attacks (SlowRead, SlowBody, Shrew, and SlowHeaders).

## Environment Description
- We use STK to simulate the parameters of satellite networks and to generate satellite visibility reports. Based on this information, we use the ION-DTN software to construct a prototype environment. All satellite nodes are deployed on Dell PowerEdge R530 rack servers equipped with Intel Xeon E5-2603 CPUs, 32 GB of RAM, and 1 TB HDDs. Node creation and management are performed using VMware virtual machines on the VMware vSphere platform. Each virtual machine runs Ubuntu 18.04 Server with 8 virtual cores and 512 MB of RAM.
## Collection Method
- We replay various 5G traffic scenarios on the terrestrial network (https://github.com/liliMpro/source_dataset). The ground traffic is forwarded to LEO satellite nodes through a gateway. Traffic is then collected from the satellite nodes.





