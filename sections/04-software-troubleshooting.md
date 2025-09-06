# 04. Software Troubleshooting (OS & Applications) (60 Facts)

### Boot Issues
1. A failed POST may indicate missing or faulty hardware before OS boot. *(A+ 220-1102, Obj 3.1)*  
2. “Operating System not found” often means corrupted boot records or missing drives. *(3.1)*  
3. Windows Boot Manager (`bootmgr`) handles OS startup in modern systems. *(3.1)*  
4. Legacy Windows used `ntldr` for boot management. *(3.1)*  
5. The BCD (Boot Configuration Data) holds Windows boot options. *(3.1)*  
6. The GRUB bootloader is used in Linux systems. *(3.1)*  
7. macOS boots using EFI firmware and `boot.efi`. *(3.1)*  
8. Windows Safe Mode loads with minimal drivers for troubleshooting. *(3.1)*  
9. “Inaccessible Boot Device” error suggests disk driver or corruption issues. *(3.1)*  
10. Boot loops are often caused by driver failures or corrupt system files. *(3.1)*  

### Blue Screens, Crashes & Errors
11. Windows Blue Screen of Death (BSOD) indicates a critical kernel error. *(3.1)*  
12. BSODs display STOP codes to identify error causes. *(3.1)*  
13. Kernel panic is the Linux/macOS equivalent of a BSOD. *(3.1)*  
14. System restore points allow rollback after faulty updates. *(3.1)*  
15. Windows Recovery Environment (WinRE) provides startup repair tools. *(3.1)*  
16. Event Viewer logs details about crashes and errors. *(3.1)*  
17. Mini dump files contain debugging info after BSODs. *(3.1)*  
18. Device driver corruption is a common crash cause. *(3.1)*  
19. Bad RAM often leads to random system reboots. *(3.1)*  
20. Malware can trigger unexpected OS crashes. *(3.1)*  

### Application Issues
21. Application hangs often result from memory leaks. *(3.2)*  
22. Compatibility issues occur when apps are designed for older OS versions. *(3.2)*  
23. Running apps with elevated privileges can fix permission errors. *(3.2)*  
24. DLL errors indicate missing or corrupt dynamic link libraries in Windows. *(3.2)*  
25. Applications that crash immediately may be blocked by antivirus software. *(3.2)*  
26. A corrupt user profile can cause app settings to fail. *(3.2)*  
27. Linux package dependency issues prevent apps from launching. *(3.2)*  
28. macOS Gatekeeper blocks unsigned applications by default. *(3.2)*  
29. Reinstalling or repairing applications resolves corrupt installations. *(3.2)*  
30. Resource monitor tools help diagnose app performance issues. *(3.2)*  

### Malware & Performance Problems
31. Unexpected pop-ups are a common sign of adware infection. *(3.3)*  
32. Slow system performance may result from background malware. *(3.3)*  
33. Antivirus tools detect and quarantine suspicious files. *(3.3)*  
34. Ransomware encrypts files and demands payment to unlock them. *(3.3)*  
35. Keyloggers silently record keystrokes. *(3.3)*  
36. Rogue security software pretends to be antivirus but installs malware. *(3.3)*  
37. Spyware tracks user activity and sends data externally. *(3.3)*  
38. Browser redirection suggests a hijacked DNS or malicious extension. *(3.3)*  
39. Disabling suspicious startup apps can remove malware persistence. *(3.3)*  
40. Safe Mode scans can detect malware hiding during normal boot. *(3.3)*  

### Troubleshooting Utilities
41. `sfc /scannow` repairs corrupted Windows system files. *(3.4)*  
42. `chkdsk /f` fixes filesystem and disk errors. *(3.4)*  
43. `DISM /Online /Cleanup-Image` repairs Windows image corruption. *(3.4)*  
44. Task Manager identifies unresponsive processes. *(3.4)*  
45. Resource Monitor shows CPU, memory, disk, and network activity. *(3.4)*  
46. Reliability Monitor tracks historical system stability. *(3.4)*  
47. `msconfig` manages startup programs and boot options. *(3.4)*  
48. Windows Safe Mode with Networking enables internet troubleshooting. *(3.4)*  
49. Linux `top` command monitors real-time process usage. *(3.4)*  
50. macOS Activity Monitor provides app diagnostics. *(3.4)*  

### User Profiles & Permissions
51. Corrupt Windows user profiles can be rebuilt by copying default profile data. *(3.5)*  
52. Roaming profiles sync user data across domain-joined machines. *(3.5)*  
53. NTFS permissions manage file and folder access in Windows. *(3.5)*  
54. Linux uses `chmod` and `chown` for permissions and ownership. *(3.5)*  
55. macOS permissions can be reset with Disk Utility. *(3.5)*  
56. Standard user accounts reduce risk compared to administrator accounts. *(3.5)*  
57. UAC (User Account Control) prompts protect Windows from unauthorized changes. *(3.5)*  
58. Windows profiles store app data in `C:\Users\username\AppData`. *(3.5)*  
59. Profile corruption often causes missing desktop icons or settings. *(3.5)*  
60. Migrating profiles can be done with Windows User State Migration Tool (USMT). *(3.5)*  

---