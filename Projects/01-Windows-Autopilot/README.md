# Windows Autopilot Deployment

## Objective

Configure and deploy Windows Autopilot in Microsoft Intune to automatically provision a Windows 11 device during the Out-of-Box Experience (OOBE).

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Hypervisor | Oracle VirtualBox |
| Host OS | Ubuntu Linux |
| Guest OS | Windows 11 |
| Identity | Microsoft Entra ID |
| Device Management | Microsoft Intune |
| Licensing | Microsoft 365 Developer Tenant |

---

## Technologies Used

- Microsoft Intune
- Microsoft Entra ID
- Windows Autopilot
- Windows 11
- Oracle VirtualBox
- Microsoft 365 Developer Tenant

---

## Steps Performed

1. Created an Autopilot device group.
2. Captured the Windows hardware hash using PowerShell.
3. Imported the hardware hash into Windows Autopilot.
4. Verified successful device import.
5. Created a Windows Autopilot deployment profile.
6. Assigned the deployment profile to the Autopilot device group.
7. Waited for the deployment profile to assign successfully.
8. Rebooted the virtual machine into OOBE.
9. Signed in with the lab user account.
10. Verified successful Autopilot enrollment.

---

## Validation

The deployment was verified by confirming:

- Device successfully joined Microsoft Entra ID
- Device enrolled into Microsoft Intune
- Windows Autopilot profile applied successfully
- Device appeared in Intune Devices
- Device received assigned deployment profile

---

## Lessons Learned

- Learned how Windows Autopilot hardware hashes are imported.
- Learned how deployment profiles are assigned.
- Learned how Intune provisions devices during OOBE.
- Learned how device group assignments affect Autopilot deployments.

---

## Screenshots

Screenshots will be added throughout this project.
