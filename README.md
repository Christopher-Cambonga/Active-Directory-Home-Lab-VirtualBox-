# Active Directory Home Lab (Help Desk Simulation)

## Overview

This project simulates a basic enterprise Active Directory environment with a focus on common help desk responsibilities. The lab demonstrates user account management, troubleshooting, and administrative tasks typically performed in an entry-level IT support role.

## Objectives

* Deploy and configure an Active Directory Domain Controller
* Join a client machine to the domain
* Perform common help desk tasks within a domain environment
* Troubleshoot typical user and system issues

## Lab Environment

* **Domain Controller:** Windows Server (Active Directory Domain Services, DNS)
* **Client Machine:** Windows 10/11
* **Network:** Internal virtual lab environment

## Key Skills Demonstrated

### Active Directory Configuration

* Installed and configured Active Directory Domain Services (AD DS)
* Promoted server to Domain Controller
* Configured domain users and groups
* Organized users into Organizational Units (OUs)

### Help Desk Task Simulation

The following real-world IT support tasks were performed within the lab:

* **User Account Creation**

  * Created new domain users and assigned them to appropriate groups

* **Password Resets**

  * Reset user passwords and enforced password change at next login

* **Account Lockout Resolution**

  * Identified locked accounts and restored user access

* **Enable/Disable User Accounts**

  * Managed user access based on simulated scenarios (e.g., employee onboarding/offboarding)

* **Basic Troubleshooting**

  * Diagnosed and resolved domain join issues
  * Resolved login/authentication problems
  * Verified proper DNS configuration for domain connectivity


## Example Scenario

A user was unable to log in due to repeated failed password attempts. The account was identified as locked in Active Directory, unlocked, and a password reset was performed. The user was then able to successfully authenticate to the domain.

## What I Learned

* Core Active Directory concepts and structure
* How user and group management works in a domain environment
* The role of DNS in domain functionality
* Common help desk workflows and troubleshooting steps
* How to approach and resolve user access issues

## Future Improvements

* Implement Remote Desktop (RDP) for remote support scenarios
* Add PowerShell automation for user management tasks
* Integrate basic log monitoring for security visibility

## Screenshots

See the `/screenshots` folder for examples of the lab setup and tasks performed.

## Author
Christopher Cambonga

