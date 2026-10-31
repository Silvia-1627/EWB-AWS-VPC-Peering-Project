# AWS VPC Peering Project – EWB Cloud Labs

## Project Overview
This project demonstrates secure network connectivity between two Amazon Virtual Private Clouds (VPCs) using VPC Peering in the AWS Mumbai Region (`ap-south-1`).

The project was completed as part of the EWB Cloud Labs AWS internship.

## Architecture
- **VPC A:** `10.10.0.0/16`
- **VPC B:** `10.20.0.0/16`
- **Region:** Asia Pacific (Mumbai) – `ap-south-1`
- **Connectivity:** VPC Peering
- **EC2:** Bastion host, App-A and App-B

## Implementation
- Created two VPCs and three subnets.
- Configured an Internet Gateway and route tables.
- Established VPC Peering.
- Configured security group rules.
- Tested SSH connectivity and bidirectional ICMP communication.
- Performed a controlled ICMP failure test and restored connectivity.
- Completed AWS resource cleanup after testing.

## Testing Results
- SSH access to App-B through the Bastion host: Successful.
- App-A to App-B ping: Successful.
- App-B to App-A ping: Successful.
- Controlled ICMP failure: Demonstrated.
- Connectivity recovery: Successful.

## Project Files
- `EWB_VPC_Peering_Report.pdf` – Project report and architecture details.
- `EWB_VPC_Peering_Evidence.zip` – Screenshots and supporting evidence.

## Cleanup
All project EC2 instances and associated VPC resources were cleaned up after testing.

## Author
Silvia Singh

**Project:** EWB AWS VPC Peering  
**Region:** AWS Mumbai (`ap-south-1`)
