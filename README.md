# azure-oss-iaas
Azure IaaS Deployment for OSS Corporation
# Azure IaaS Deployment for OSS Corporation

## 🧩 Business Scenario

OSS Corporation is a globally distributed firm with its headquarters in East US and a branch office in Southeast Asia. They plan to host:

- **Data Tier**: In East US (Headquarters)
- **Application Tier**: In Southeast Asia (Branch)

## 🎯 Objective

Deploy Azure Infrastructure as a Service (IaaS) VMs in both regions, with secure, private communication using VNet peering between:

- `HQ-VNet` (East US) – Data Tier
- `Branch-VNet` (Southeast Asia) – App Tier

## 🛠️ Key Deliverables

- Terraform or ARM templates for deploying VNets and VMs
- Azure CLI scripts to configure and peer VNets
- Screenshots of deployed infrastructure and ping test
- Verification logs of VM connectivity (Ping)
