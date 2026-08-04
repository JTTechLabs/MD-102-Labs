# Microsoft Intune MD-102 Lab

## Overview

This repository documents my hands-on Microsoft Intune and Windows Autopilot lab built in my personal Microsoft 365 developer tenant.

The purpose of this lab is to gain practical experience with endpoint management technologies covered in the Microsoft MD-102 certification while building a portfolio of real-world Intune administration skills.

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Hypervisor | Oracle VirtualBox |
| Host OS | Ubuntu Linux |
| Guest OS | Windows 11 Pro |
| Identity | Microsoft Entra ID |
| Device Management | Microsoft Intune |
| Licensing | Microsoft 365 E5 Developer Tenant |

---

## Technologies Used

- Microsoft Intune
- Microsoft Entra ID
- Windows Autopilot
- Enrollment Status Page (ESP)
- Company Portal
- Win32 Application Deployment
- Microsoft 365
- PowerShell
- VirtualBox
- Windows 11

---

# Project 1 - Windows Autopilot Deployment

## Objective

Deploy a Windows 11 device using Windows Autopilot from OOBE through enrollment into Microsoft Intune.

### Completed

- [x] Created Microsoft 365 developer tenant
- [x] Configured Microsoft Intune
- [x] Created Autopilot deployment profile
- [x] Captured hardware hash
- [x] Imported Autopilot device
- [x] Assigned Autopilot profile
- [x] Successfully completed Autopilot deployment

---

# Project 2 - Enrollment Status Page (ESP)

## Objective

Configure ESP to require applications during device enrollment.

### Completed

- [x] Created custom ESP profile
- [x] Configured blocking applications
- [x] Tested successful deployment

---

# Project 3 - Win32 Application Deployment

Applications deployed:

- Company Portal
- Google Chrome
- 7-Zip

---

# Project 4 - Compliance Policies

## Tested

- Windows 11 Compliance Policy
- BitLocker Compliance Policy

---

# Project 5 - Conditional Access

- Report-only testing
- User assignments
- Initial policy validation

---

# Troubleshooting

## Issue

Device authentication failure after reboot.

### Symptoms

- DeviceAuthStatus = FAILED
- Work account required repair
- Windows Hello PIN reset
- Device compliance errors

### Troubleshooting Performed

- Verified Entra ID Join
- Verified Intune enrollment
- Verified DeviceAuthStatus
- Tested Windows Time service
- Reviewed compliance policies
- Investigated BitLocker configuration
- Compared healthy vs unhealthy deployments

Status:

> Investigation ongoing.

---

# Screenshots

Screenshots will be added throughout the lab documentation.

---

# Next Steps

- Configuration Profiles
- Windows Update Rings
- Endpoint Security
- Microsoft Defender
- PowerShell Deployment
- Proactive Remediations
- Device Restrictions
