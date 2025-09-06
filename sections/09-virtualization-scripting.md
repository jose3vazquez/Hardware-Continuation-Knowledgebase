
# 09. Virtualization & Scripting Basics (60 Facts)

### Virtualization Concepts  
1. Virtualization allows multiple OSes to run on a single physical machine. *(A+ 220-1101, Obj 4.1)*  
2. A hypervisor is software that creates and manages virtual machines. *(4.1)*  
3. Type 1 hypervisors run directly on hardware (bare-metal). *(4.1)*  
4. Type 2 hypervisors run on top of an existing OS. *(4.1)*  
5. Examples of Type 1 hypervisors: VMware ESXi, Microsoft Hyper-V. *(4.1)*  
6. Examples of Type 2 hypervisors: VirtualBox, VMware Workstation. *(4.1)*  
7. Virtual machines (VMs) emulate hardware resources like CPU, RAM, and NICs. *(4.1)*  
8. Snapshots capture VM state for easy rollback. *(4.1)*  
9. Templates allow rapid deployment of identical VMs. *(4.1)*  
10. Thin provisioning allocates storage as needed instead of reserving upfront. *(4.1)*  

### Cloud vs Virtualization  
11. Virtualization is the foundation for most cloud services. *(4.1)*  
12. Cloud computing offers shared, on-demand resources. *(4.1)*  
13. IaaS provides virtual machines and storage. *(4.1)*  
14. SaaS delivers complete software solutions over the internet. *(4.1)*  
15. PaaS provides development platforms with pre-built tools. *(4.1)*  
16. VDI (Virtual Desktop Infrastructure) hosts desktops on central servers. *(4.1)*  
17. Thin clients rely on VDI/cloud, not local resources. *(4.1)*  
18. Thick clients run full OS and apps locally. *(4.1)*  
19. Containerization (Docker, Kubernetes) is lighter than full VM virtualization. *(4.1)*  
20. Containers share the host OS kernel. *(4.1)*  

### Virtual Networking  
21. VMs use virtual NICs (vNICs) to connect to physical or virtual networks. *(4.1)*  
22. Bridged networking connects VMs directly to the host’s network. *(4.1)*  
23. NAT networking shares the host IP for VM internet access. *(4.1)*  
24. Host-only networking isolates VMs from external networks. *(4.1)*  
25. VLAN tagging can segment virtual traffic within a host. *(4.1)*  
26. Virtual switches connect VMs internally and to physical networks. *(4.1)*  
27. VPN clients can run inside VMs for secure tunnels. *(4.1)*  
28. Firewalls can be virtualized for VM segmentation. *(4.1)*  
29. Cloud VMs often include security groups for traffic rules. *(4.1)*  
30. Hybrid networking links local VMs with cloud resources. *(4.1)*  

### Scripting Fundamentals  
31. Scripting automates repetitive IT tasks. *(A+ 220-1102, Obj 4.8)*  
32. Batch files (.bat) are common for Windows automation. *(4.8)*  
33. PowerShell is a task automation framework for Windows. *(4.8)*  
34. Linux/Unix scripts are commonly written in Bash. *(4.8)*  
35. Python is cross-platform and widely used for IT automation. *(4.8)*  
36. Scripts are usually interpreted rather than compiled. *(4.8)*  
37. Variables store data for later use in scripts. *(4.8)*  
38. Conditional statements (if/else) control script logic. *(4.8)*  
39. Loops (for/while) repeat actions multiple times. *(4.8)*  
40. Functions group reusable code blocks. *(4.8)*  

### Common Script Examples  
41. Batch scripts often automate file management tasks. *(4.8)*  
42. PowerShell can manage Active Directory accounts. *(4.8)*  
43. Bash scripts commonly manage system updates in Linux. *(4.8)*  
44. Python is used for parsing logs or API automation. *(4.8)*  
45. Cron jobs schedule scripts on Unix-like systems. *(4.8)*  
46. Task Scheduler automates script execution in Windows. *(4.8)*  
47. Scripts can automate system monitoring tasks. *(4.8)*  
48. Logging can be scripted for troubleshooting. *(4.8)*  
49. Scripts can call system commands (ping, nslookup). *(4.8)*  
50. Scripting supports DevOps automation pipelines. *(4.8)*  

### Security & Best Practices  
51. Scripts should validate inputs to avoid errors. *(4.8)*  
52. Hardcoding credentials in scripts is insecure. *(4.8)*  
53. Secure scripts using environment variables for secrets. *(4.8)*  
54. Test scripts in a sandbox before production use. *(4.8)*  
55. Version control (Git) helps track script changes. *(4.8)*  
56. Script execution policies (in PowerShell) restrict unsigned scripts. *(4.8)*  
57. Use comments to document script functionality. *(4.8)*  
58. Error handling ensures scripts fail gracefully. *(4.8)*  
59. Scheduling automation reduces human error. *(4.8)*  
60. Documentation is essential for script maintainability. *(4.8)*  

---

📊 **Category Total: 60 Facts** (fully exam-aligned, non-repetitive)
