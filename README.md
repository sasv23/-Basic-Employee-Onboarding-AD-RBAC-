# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The problem started in the fictional company called Northstar Medical Group. They are growing quickly and passed their responsibility for the identity lifecycle workflow to a third-party app. Issues began to arise; there was no RBAC policy in place, and users were assigned access AD-HOC. There were no audit trails, and there were plenty of HIPAA risks for a company that has more than 200 employees.

## Solution Overview
* The solution was to build a basic employee onboarding pipeline in Active Directory. One main fix I did involved setting up the RBAC matrix and ensuring users were given access ONLY according to their role. 15 users were created, all in correct placements. I also simulated a mock ticket where a user was provisioned the incorrect level of access.

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
* Sorted various users to specific OUs & Security Groups
* Provisioned 15 user accounts with proper standards



