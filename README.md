# HyperVTools

<p align="center">
  <img src="images/HVT-256.png" alt="HyperVTools Logo" width="128">
</p>

<p align="center">
  <strong>A free inventory and documentation tool for Microsoft Hyper-V environments</strong>
</p>

<p align="center">
  <a href="https://hypervtools.net">Website</a> |
  <a href="https://github.com/rlaneo/hypervtools/releases">Download</a> |
  <a href="https://github.com/rlaneo/hypervtools/wiki">Documentation</a> |
  <a href="https://github.com/rlaneo/hypervtools/issues">Report Issues</a>
</p>

---

## About

HyperVTools is inspired by [RVTools](https://www.robware.net/rvtools/) for VMware. Special thanks to Rob de Veij for creating RVTools, which has been an invaluable resource for VMware administrators for many years. HyperVTools aims to bring that same functionality to the Hyper-V community, providing a comprehensive view of your infrastructure in an easy-to-use interface.

## Features

| Feature | Description |
|---------|-------------|
| 12 Data Tabs | Complete visibility into VMs, CPU, Memory, Disks, Network, Checkpoints, Integration Services, Storage, Replication, DVDs, Clusters, and Hosts |
| Cluster Support | Query all nodes in a failover cluster simultaneously |
| Remote Connectivity | Connect to remote hosts with credentials, SSL, and Kerberos support |
| Export to Excel | Export all data to Excel workbooks with multiple worksheets |
| Search & Filter | Quickly find VMs across all tabs with Ctrl+F |
| Auto-Refresh | Keep data current with configurable refresh intervals (1, 5, 10 mins) |
| Health Checks | Identify potential issues like old checkpoints, missing heartbeats, and cluster imbalances |
| Color Coding | Visual indicators for power state, CPU usage, memory pressure, and checkpoint age |

## System Requirements

- Windows 11 or Windows Server 2016+
- .NET Framework 4.7.2 or later
- Hyper-V PowerShell module (for local connections)
- Network access to target Hyper-V hosts (for remote connections)

## Quick Start

1. Download the latest release from the [Releases](https://github.com/rlaneo/hypervtools/releases) page
2. Extract and run `HyperVTools.exe`
3. Enter a Hyper-V host name (or `localhost` for the local machine)
4. Click **Connect**

## Data Tabs

| Tab | Description |
|-----|-------------|
| vInfo | General VM information (name, state, CPU, memory, guest OS) |
| vCPU | CPU configuration and real-time usage |
| vMemory | Memory allocation and dynamic memory settings |
| vDisk | Virtual hard disks with size, type, and fragmentation |
| vNetwork | Network adapters, switches, VLANs, and IP addresses |
| vCheckpoint | Checkpoints (snapshots) with age tracking |
| vIntegration | Integration Services status and guest FQDN |
| vStorage | Storage locations and capacity |
| vReplication | Hyper-V Replica configuration and status |
| vDVD | DVD drives and mounted ISO files |
| vCluster | Failover cluster nodes and roles |
| vHost | Host server specifications |

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl+C | Copy selection to clipboard |
| Ctrl+F | Find/search in current tab |
| F5 | Refresh data |
| F1 | About dialog |
| Escape | Close search panel |

## License

Freeware - Free for personal and commercial use.

## Credits

- Created by Robert Lane
- Graphics by Bob Hodges
- Inspired by [RVTools](https://www.robware.net/rvtools/) by Rob de Veij
- Uses [ClosedXML](https://github.com/ClosedXML/ClosedXML) for Excel export

---

© 2026 Robert Lane | [hypervtools.net](https://hypervtools.net)
