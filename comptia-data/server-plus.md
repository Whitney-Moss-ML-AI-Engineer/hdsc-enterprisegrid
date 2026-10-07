# CompTIA Server+ (SK0-005) — Terminology Inventory

## Domains and Percentage Weights
1. **1.0 Server Hardware Installation and Management** — 18%
2. **2.0 Server Administration** — 30%
3. **3.0 Security and Disaster Recovery** — 24%
4. **4.0 Troubleshooting** — 28%

## 1.0 Server Hardware
- Rack units (1U/2U/3U), PDU, KVM, rail kits, UPS, cabling (twisted pair, fiber SC/LC, single/multi-mode, 10GigE), SFP/SFP+/QSFP+, chassis types (tower, rack mount, blade enclosure), HCL, CPU, GPU
- Storage: RAID 0/1/5/6/10, JBOD, hardware vs. software RAID, HDD RPM (7200/10000/15000), SSD (read/write intensive), SAS/SATA/PCI/eSATA/USB/SD interfaces, NAS/NFS/CIFS, SAN, iSCSI, Fibre Channel/FCoE
- Maintenance: out-of-band management (IP KVM), hot-swappable drives/cards/PSUs/fans, firmware upgrades, BIOS/UEFI

## 2.0 Server Administration
- OS installation: GUI/Core/bare metal/virtualized/remote/unattended, imaging, cloning, P2V, GPT/MBR, LVM, filesystems (ext4, NTFS, VMFS, ReFS, ZFS)
- Network services: VLAN, DNS, FQDN, IPv4/RFC1918/IPv6, firewall/ports, DHCP, APIPA, MAC addresses
- Server roles: print, database, file, web, application, messaging; disk quotas, compression, deduplication; monitoring (uptime, IOPS, CPU, memory, event logs); Robocopy, SCP
- High availability: clustering (active-active, active-passive, failover/failback, heartbeat), fault tolerance, load balancing, NIC teaming, link aggregation
- Virtualization: host/guest, bridged/NAT, vNICs/virtual switches, resource overprovisioning, public/private/hybrid cloud
- Scripting: Bash, Batch, PowerShell, VBS
- Asset management: BIA, MTBF, MTTR, RPO, RTO, SLA
- Licensing: per-instance, per-concurrent-user, per-server, per-socket, per-core, site-based, node-locked

## 3.0 Security and Disaster Recovery
- Data security: encryption at rest/in transit, UEFI/BIOS/bootloader passwords
- Physical security: bollards, guards, cameras, biometric, RFID, access control vestibules, fire suppression, HVAC
- IAM: role/rule-based permissions, MFA, SSO, auditing
- Risk mitigation: DLP, SIEM, PII, PCI DSS
- Hardening: disable unused services/ports, firewall config, HIDS/HIPS, antivirus/anti-malware
- Decommissioning: disk wiping, degaussing, shredding, crushing, incineration
- Backups: full, synthetic full, incremental, differential, archive, open file, snapshot; tape/cloud/disk media
- Disaster recovery: hot/cold/warm site, cloud; replication (constant, synchronous/asynchronous), mirroring, tabletops

## 4.0 Troubleshooting
- Methodology (identify, theorize, test, plan, verify, document)
- Hardware: LED/LCD panel codes, POST codes, BSOD, kernel panic, CMOS battery, ESD
- Storage: boot errors, HBA failure, RAID/array management tools, `net use`/`mount`
- OS/software: patching, Safe Mode, NTP, SCCM, Puppet/Chef/Ansible, GPO, `runas`/`sudo`/`su`
- Network: `ipconfig`, `ip addr`, `ping`, `tracert`/`traceroute`, `nslookup`, `netstat`, `dig`, `telnet`, `nc`, `nbtstat`, `route`
- Security: port scanners, sniffers, anti-malware, checksums, SELinux, UAC
