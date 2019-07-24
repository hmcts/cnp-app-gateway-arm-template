# cnp-app-gateway-arm-template

This repository contains ARM (Azure Resource Manage) template to provision an Azure Application Gateway, which conforms to the requirements of the MoJ (Ministry of Justice).

Below are some of the characteristics of the Application Gateway.

PublicIp: Statically Assigned.
Version: V2.
Networking: Deployed in to a dedicated subnet.
FirewallMode: Prevention.
OWASP: 3.0.


### Notes
Please note this does not create all the required dependencies for the Application Gateway. Below are pre-requisites expected to be in place before the Application Gateway can be deployed.

* Virtual Network
* Subnet
* Public Facing Certificates.
