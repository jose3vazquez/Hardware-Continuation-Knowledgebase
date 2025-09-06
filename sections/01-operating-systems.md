# 01. Operating Systems (60 Facts)

### Windows Basics
1. Windows 10 introduced a unified codebase for desktop, tablet, and hybrid devices. *(A+ 220-1102, Obj 1.2)*  
2. Windows 11 requires Secure Boot and TPM 2.0 for installation. *(1.2)*  
3. Windows Home editions lack advanced features like Group Policy and BitLocker. *(1.2)*  
4. Windows Pro editions include domain join, Remote Desktop host, and Hyper-V. *(1.2)*  
5. The Windows Registry is a hierarchical database storing system and application settings. *(1.5)*  
6. Windows File Explorer supports file compression with NTFS, ZIP, and third-party formats. *(1.3)*  
7. Task Manager shows processes, performance, and startup programs. *(1.4)*  
8. Windows Device Manager displays installed hardware and drivers. *(1.4)*  
9. Windows Update supports security patches, feature upgrades, and driver updates. *(1.6)*  
10. Windows Event Viewer logs system, application, and security events. *(1.6)*  

### Linux Basics
11. Linux distributions are built around the Linux kernel and package managers. *(1.8)*  
12. Common Linux shells include Bash, Zsh, and Fish. *(1.9)*  
13. Linux file systems include ext4, XFS, Btrfs, and ZFS. *(1.5)*  
14. `/etc` contains system configuration files in Linux. *(1.5)*  
15. The root user has unrestricted administrative privileges. *(1.5)*  
16. Linux permissions use rwx notation for user, group, and others. *(1.5)*  
17. Package managers include `apt` (Debian/Ubuntu) and `dnf` (Red Hat/Fedora). *(1.8)*  
18. System logs are stored in `/var/log`. *(1.6)*  
19. `systemctl` is used to manage services on systemd-based distros. *(1.6)*  
20. `cron` and `at` are used for scheduling tasks in Linux. *(1.6)*  

### macOS Basics
21. macOS is UNIX-certified and uses the Darwin kernel. *(1.2)*  
22. The Finder is macOS’s file management interface. *(1.2)*  
23. System Preferences (macOS ≤12) / System Settings (macOS ≥13) control OS configuration. *(1.2)*  
24. Time Machine is macOS’s built-in backup utility. *(1.6)*  
25. Spotlight search indexes files and applications for quick access. *(1.2)*  
26. macOS applications are bundled into `.app` packages. *(1.3)*  
27. Gatekeeper prevents unsigned applications from running by default. *(1.6)*  
28. Disk Utility manages partitions, file systems, and disk repair. *(1.5)*  
29. `Terminal` provides command-line access to UNIX tools. *(1.9)*  
30. macOS supports HFS+, APFS, and FAT32/exFAT file systems. *(1.5)*  

### Mobile OS (iOS & Android)
31. iOS does not allow third-party app stores (except limited EU exceptions). *(1.7)*  
32. Android allows apps from Google Play or side-loaded APKs. *(1.7)*  
33. iOS uses the Apple File System (APFS) for storage. *(1.5)*  
34. Android commonly uses ext4 or F2FS file systems. *(1.5)*  
35. Mobile OS updates may be controlled by the carrier (Android) or manufacturer (Apple). *(1.6)*  
36. Mobile device management (MDM) enforces security policies on smartphones. *(1.7)*  
37. Hotspot/tethering turns a mobile device into a network gateway. *(1.7)*  
38. Both iOS and Android support VPN profiles for remote work. *(1.7)*  
39. iOS uses iCloud for backup/sync, Android uses Google Drive. *(1.6)*  
40. Jailbreaking/rooting removes OS restrictions but increases security risks. *(1.6)*  

### File Systems & Permissions
41. FAT32 supports maximum 4 GB files, while exFAT removes that limit. *(1.5)*  
42. NTFS supports file-level encryption (EFS), compression, and journaling. *(1.5)*  
43. APFS is optimized for SSD performance and snapshots. *(1.5)*  
44. Linux permissions use `chmod` to assign read/write/execute rights. *(1.5)*  
45. ACLs (Access Control Lists) extend traditional file permissions. *(1.5)*  
46. Hidden files in Linux/macOS begin with a dot (`.`). *(1.5)*  
47. Windows hidden files require enabling “Show hidden items” in Explorer. *(1.5)*  
48. File extensions in Windows are used for file association, not required in Linux/macOS. *(1.3)*  
49. System files are often protected and require elevated permissions to modify. *(1.5)*  
50. File integrity is verified with hashes (MD5, SHA256). *(1.5)*  

### Command-Line Utilities (Cross-OS)
51. `ipconfig` (Windows) and `ifconfig`/`ip` (Linux) display network settings. *(1.9)*  
52. `ping` tests reachability of hosts across OSes. *(1.9)*  
53. `tracert` (Windows) / `traceroute` (Linux/macOS) traces network paths. *(1.9)*  
54. `netstat` shows network connections and open ports. *(1.9)*  
55. `nslookup` and `dig` query DNS records. *(1.9)*  
56. `tasklist` (Windows) and `ps` (Linux/macOS) list running processes. *(1.9)*  
57. `kill` and `taskkill` terminate processes. *(1.9)*  
58. `sfc /scannow` checks Windows system files. *(1.9)*  
59. `chkdsk` verifies and repairs disk errors in Windows. *(1.9)*  
60. `grep` searches text patterns in Linux/macOS files. *(1.9)*  

---