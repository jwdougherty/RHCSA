# RHCSA
## Notes on RHCSA objectives

Study points for the exam

    RHCSA exam candidates should be able to accomplish the tasks below without assistance. These have been grouped into several categories.
### Understand and use essential tools

<details>
    <summary>01. Access a shell prompt and issue commands with correct syntax</summary>
    ## Header
    1. list
    2. Notes             
    3. terminal app
    4. - tty through ctl+alt+f1-f6
</details>    
<details>
    <summary>02. Use input-output redirection (>, >>, |, 2>, etc.)</summary>
</details>
<details>
    <summary>03. Use grep and regular expressions to analyze text</summary>
</details>
<details>
    <summary>04. Access remote systems using SSH</summary>
</details>
<details>
    <summary>05. Log in and switch users in multiuser targets</summary>
</details>
<details>
    <summary>06. Archive, compress, unpack, and uncompress files using tar, star, gzip, and bzip2</summary>
</details>
<details>
    <summary>07. Create and edit text files</summary>
</details>
<details>
    <summary>08. Create, delete, copy, and move files and directories</summary>
</details>
<details>
    <summary>09. Create hard and soft links</summary>
</details>
<details>
    <summary>10. List, set, and change standard ugo/rwx permissions</summary>
</details>
<details>
    <summary>11. Locate, read, and use system documentation including man, info, and files in /usr/share/doc</summary>
</details>    

### Create simple shell scripts

12. Conditionally execute code (use of: if, test, [], etc.)
13. Use Looping constructs (for, etc.) to process file, command line input
14. Process script inputs ($1, $2, etc.)
15. Processing output of shell commands within a script

### Operate running systems

16. Boot, reboot, and shut down a system normally
17. Boot systems into different targets manually
18. Interrupt the boot process in order to gain access to a system
19. Identify CPU/memory intensive processes and kill processes
20. Adjust process scheduling
21. Manage tuning profiles
22. Locate and interpret system log files and journals
23. Preserve system journals
24. Start, stop, and check the status of network services
25. Securely transfer files between systems

### Configure local storage

26. List, create, delete partitions on MBR and GPT disks
27. Create and remove physical volumes
28. Assign physical volumes to volume groups
29. Create and delete logical volumes
30. Configure systems to mount file systems at boot by universally unique ID (UUID) or label
31. Add new partitions and logical volumes, and swap to a system non-destructively

### Create and configure file systems

32. Create, mount, unmount, and use vfat, ext4, and xfs file systems
33. Mount and unmount network file systems using NFS
34. Configure autofs
35. Extend existing logical volumes
36. Create and configure set-GID directories for collaboration
37. Diagnose and correct file permission problems

### Deploy, configure, and maintain systems

38. Schedule tasks using at and cron
39. Start and stop services and configure services to start automatically at boot
40. Configure systems to boot into a specific target automatically
41. Configure time service clients
42. Install and update software packages from Red Hat Network, a remote repository, or from the local file system
43. Modify the system bootloader

### Manage basic networking

44. Configure IPv4 and IPv6 addresses
45. Configure hostname resolution
46. Configure network services to start automatically at boot
47. Restrict network access using firewall-cmd/firewall

### Manage users and groups

48. Create, delete, and modify local user accounts
49. Change passwords and adjust password aging for local user accounts
50. Create, delete, and modify local groups and group memberships
51. Configure superuser access

### Manage security

52. Configure firewall settings using firewall-cmd/firewalld
53. Manage default file permissions
54. Configure key-based authentication for SSH
55. Set enforcing and permissive modes for SELinux
56. List and identify SELinux file and process context
57. Restore default file contexts
58. Manage SELinux port labels
59. Use boolean settings to modify system SELinux settings
60. Diagnose and address routine SELinux policy violations

### Manage containers

61. Find and retrieve container images from a remote registry
62. Inspect container images
63. Perform container management using commands such as podman and skopeo
64. Build a container from a Containerfile
65. Perform basic container management such as running, starting, stopping, and listing running containers
66. Run a service inside a container
67. Configure a container to start automatically as a systemd service
68. Attach persistent storage to a container

As with all Red Hat performance-based exams, configurations must persist after reboot without intervention.
