# Windows Autopilot Deployment

## Overview

This project demonstrates a complete Windows Autopilot deployment using Microsoft Intune within a Microsoft 365 Developer tenant.

The deployment covers:

- Windows Autopilot registration
- Online hardware hash upload
- Autopilot profile assignment
- Out-of-Box Experience (OOBE)
- Enrollment Status Page (ESP)
- Windows Hello for Business
- Microsoft Intune enrollment
- Win32 application deployment
- Deployment validation

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Hypervisor | Oracle VirtualBox |
| Host OS | Ubuntu Linux |
| Guest OS | Windows 11 |
| Identity | Microsoft Entra ID |
| MDM | Microsoft Intune |
| Deployment | Windows Autopilot |

---

# Deployment Walkthrough

## 1. Region Selection

The Windows 11 Out-of-Box Experience begins.

![](Images/01-OOBE-Region.png)

---

## 2. Launch PowerShell

PowerShell was opened during OOBE to collect the hardware hash.

![](Images/03-Powershell.png)

---

## 3. Upload Hardware Hash

The device hardware hash was uploaded directly into Microsoft Intune using the Online method.

![](Images/04-Autopilot-OnlineUpload-Success.png)

---

## 4. Device Imported

The device successfully appeared within Windows Autopilot Devices.

![](Images/05-Autopilot-DeviceImported.png)

---

## 5. Autopilot Profile Assigned

The deployment profile was automatically assigned.

![](Images/06-Autopilot-ProfileAssigned.png)

---

## 6. Organization Sign-In

Windows recognized the device as an organizational Autopilot deployment.

![](Images/07-OOBE-OrganizationSignIn.png)

---

## 7. User Authentication

Signed in using the Microsoft Intune licensed user account.

![](Images/08-UserSignIn.png)

---

## 8. Device Preparation

Autopilot began preparing the device for deployment.

![](Images/09-Preparing-Your-Device.png)

---

## 9. Enrollment Status Page

The Enrollment Status Page started processing required policies and applications.

![](Images/10-ESP-Started.png)

![](Images/11-ESP-DevicePreparation.png)

---

## Skills Demonstrated

- Microsoft Intune
- Windows Autopilot
- Microsoft Entra ID
- Windows Hello for Business
- Enrollment Status Page
- Win32 App Deployment
- Endpoint Management
- Device Enrollment
- Troubleshooting
