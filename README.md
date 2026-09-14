# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The issue in this project is related to a fictional company called "NorthStar Medical Group". Their Company is expanding rapidly expanding and they expanded their Identity Lifestyle workflow to a third party MSP. In the beginning this was fine. But as their company grew the issues started to show. Their was lack of structure and within this IT Infrastructure. Users were assigned access to AD-HOC. There was no Audit trails and on top of that, HIPAA risks.

## Solution Overview
The Solution was to build out a basic employee onboarding pipeline in active direction. I set up the RBAC matrix and ensured users were given access ONLY to their role. I also simulated a mock ticket where a user was provisioned the incorrect level of access!

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)

