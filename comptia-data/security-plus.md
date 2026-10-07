# CompTIA Security+ (SY0-601) — Defensive/Control Terminology Inventory

## Domains and Percentage Weights
1. **1.0 Threats, Attacks, and Vulnerabilities** — 24% (attack types noted as categories only)
2. **2.0 Architecture and Design** — 21%
3. **3.0 Implementation** — 25%
4. **4.0 Operations and Incident Response** — 16%
5. **5.0 Governance, Risk, and Compliance** — 14%

## 2.0 Architecture and Design
- Data protection: DLP, masking, encryption (at rest/in transit/in processing), tokenization, rights management, HSM, CASB, SSL/TLS inspection, hashing
- Site resiliency: hot/cold/warm site; deception tech: honeypots, honeyfiles, honeynets, DNS sinkhole
- Cloud: IaaS/PaaS/SaaS/XaaS, public/community/private/hybrid, CSP, MSP/MSSP, fog/edge computing, containers/microservices, SDN/SDV, serverless, transit gateway, VM sprawl/escape
- Secure dev/deployment: provisioning/deprovisioning, secure coding (input validation, stored procedures, obfuscation), OWASP, CI/CD, elasticity/scalability, version control
- Authentication: directory services, federation, TOTP/HOTP, SMS/token/push, smart card, biometrics (fingerprint, retina, iris, facial, voice), MFA, AAA
- Resilience: redundancy (geographic, RAID, NIC teaming, UPS/generator), replication (SAN, VM), backups (full/incremental/snapshot/differential), high availability
- Embedded/specialized systems: Raspberry Pi, FPGA, Arduino, SCADA/ICS, IoT, VoIP, HVAC, RTOS, SoC, 5G, Zigbee
- Physical security: bollards, mantraps, badges, cameras/CCTV, biometric/electronic locks, Faraday cages, DMZ, secure destruction (degaussing, shredding)
- Cryptography: digital signatures, key stretching, salting, ECC, PFS, blockchain, symmetric/asymmetric encryption, steganography, homomorphic encryption

## 3.0 Implementation
- Secure protocols: DNSSEC, SSH, S/MIME, SRTP, LDAPS, FTPS/SFTP, SNMPv3, HTTPS, IPSec (AH/ESP)
- Endpoint protection: antivirus/anti-malware, EDR, DLP, NGFW, HIPS/HIDS, UEFI boot security, TPM, SED/FDE, sandboxing
- Network design: load balancing, VLAN/DMZ segmentation, zero trust, VPN (site-to-site, split tunnel, IPSec, SSL/TLS, L2TP), NAC, port security (BPDU guard, DHCP snooping, MAC filtering), jump servers, proxy servers, NIDS/NIPS, WAF, UTM, ACL
- Wireless security: WPA2/WPA3, CCMP, SAE, EAP/PEAP/EAP-TLS, 802.1X, RADIUS Federation, PSK, WPS
- Mobile security: MDM, MAM, UEM, geofencing, containerization, BYOD/COPE/CYOD, VDI
- Cloud security: CASB, security groups, VPC endpoints, container security
- Identity/access: IdP, SSO, SAML, TACACS+, OAuth, OpenID, Kerberos, RBAC/ABAC/MAC/DAC
- PKI: CA, RA, CRL, OCSP, CSR, SAN/wildcard certificates, DER/PEM/PFX formats

## 4.0 Operations and Incident Response
- Assessment tools: tracert, nslookup, nmap, netstat, tcpdump, Wireshark, OpenSSL, Nessus
- Incident response lifecycle: preparation, identification, containment, eradication, recovery, lessons learned; MITRE ATT&CK, Cyber Kill Chain, Diamond Model
- Data sources: SIEM dashboards, syslog, netflow/sflow
- Mitigation: application whitelisting/blacklisting, quarantine, SOAR runbooks/playbooks
- Digital forensics: chain of custody, order of volatility, hashing/checksums, e-discovery

## 5.0 Governance, Risk, and Compliance
- Frameworks/regulations: GDPR, PCI DSS, CIS benchmarks, NIST RMF/CSF, ISO 27001/27002/27701/31000, SOC 2 Type I/II, CSA Cloud Control Matrix
- Policies: AUP, job rotation, separation of duties, least privilege, NDA, onboarding/offboarding
- Risk management: risk register, SLE/ALE/ARO, BIA (RTO/RPO/MTTR/MTBF)
- Privacy: PII, data classification, data minimization, DPO

## Proposed Hardware/Software List
Kali Linux/ParrotOS, SIEM, Wireshark, Metasploit, tcpdump, firewall, UTM, wireless access point, cloud provider access, IoT devices.
