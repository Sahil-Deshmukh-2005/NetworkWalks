# Week 1 – VirtualBox and Kali Linux Environment Setup

## 1. Objective

The objective of Week 1 is to establish a virtualized cybersecurity lab environment using Oracle VirtualBox and Kali Linux.

The setup involves configuring Kali Linux as the attacking machine, creating an isolated NAT Network, enabling host-to-guest file sharing, and providing internet connectivity.

## 2. Tools and Technologies

- **Virtualization:** Oracle VirtualBox 7.2.16
- **Operating System:** Kali Linux 2026.1 (64-bit)
- **Host Operating System:** Linux Mint 22.3
- **Network Type:** NAT Network
- **Network Subnet:** 10.0.0.0/24
- **Guest IP Address:** 10.0.0.2/24

## 3. Virtual Machine Configuration

| Configuration | Value |
|---|---|
| VM Name | NetworkWalks-Kali |
| Operating System | Kali Linux (Debian 64-bit) |
| RAM | Approximately 4 GB |
| CPU Cores | 3 |
| Virtual Disk | 25 GB |
| Firmware | BIOS |
| Network Adapter | NAT Network |
| NAT Network Name | NatNetwork |
| Boot Device | DVD / Optical Drive |

## 4. Network Configuration

A NAT Network is used to provide network connectivity to the Kali virtual machine.

| Parameter | Configuration |
|---|---|
| Network Type | NAT Network |
| Network Name | NatNetwork |
| Network Address | 10.0.0.0 |
| Subnet Mask | 255.255.255.0 |
| Kali IP Address | 10.0.0.2 |
| CIDR | /24 |

The Kali machine is configured to use a static IP address of `10.0.0.2/24`.

The NAT Network provides internet access and communication between virtual machines connected to the same network.

## 5. Shared Folder Configuration

A shared folder enables file exchange between the Linux host and Kali Linux guest.

**Configuration:**
- Host folder: `/downloads`
- Guest mount point: `/downloads`
- Auto-mount: Enabled
- Make Permanent: Enabled
- Access: Read and Write

## 6. Clipboard and Drag-and-Drop

The following VirtualBox features are configured:

- Shared Clipboard: Bidirectional
- Drag and Drop: Bidirectional

These features allow data and files to be transferred between the host and guest operating systems.

## 7. Implementation Steps

1. Install Oracle VirtualBox.
2. Download the Kali Linux installer ISO.
3. Create a new Kali Linux virtual machine.
4. Allocate RAM, CPU cores, and virtual disk space.
5. Attach the Kali Linux ISO to the virtual optical drive.
6. Configure the NAT Network with subnet `10.0.0.0/24`.
7. Install Kali Linux.
8. Configure the static IP address `10.0.0.2/24`.
9. Enable internet connectivity.
10. Configure shared clipboard and drag-and-drop.
11. Configure the shared `/downloads` folder.
12. Verify network connectivity and file sharing.

## 8. Verification and Testing

| Test | Expected Result |
|---|---|
| Kali VM Boot | Kali Linux starts successfully |
| IP Configuration | 10.0.0.2/24 |
| Network Connectivity | NAT Network connection works |
| Internet Connectivity | External websites are reachable |
| Shared Clipboard | Copy and paste between host and guest |
| Drag and Drop | File transfer works |
| Shared Folder | `/downloads` accessible from Kali |

## 9. Conclusion

Week 1 focuses on establishing a virtualized cybersecurity laboratory using VirtualBox and Kali Linux.

The environment is designed to provide an isolated networking setup with internet connectivity, static IP configuration, and host-to-guest file-sharing capabilities. This laboratory will serve as the foundation for subsequent cybersecurity practical exercises.
