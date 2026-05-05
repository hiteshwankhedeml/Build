# Connectivity - Role of SCC

* SAP Cloud Connector
* SAP BTP is on cloud, so it can connect to any cloud system
* Destination concept is same concept as that of SAP RFC connection
* Destination can point to different systems
* For the system which are on internet, we just need to create destination
* SAP On-premise is behind firewall
* For this also we need to create Destination
* In addition, we need cloud connector to allow secure connection to on premise system
* Developer will create destination
* BASIS will create cloud connection on a VM
* Cloud connector will be binded with BTP account
* It will listen only to the traffic coming from the BTP account

**Steps:**

1. Install SAP cloud connector
2. Configure cloud connector
3. Check the connectivity from BTP
4. Register on-premise system in CC
5. Create a destination in SAP BTP
6. Smoke test
