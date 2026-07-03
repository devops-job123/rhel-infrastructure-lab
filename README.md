# RHEL Infrastructure Lab

## Overview
This project simulates a real enterprise Linux environment using RHEL 9. It includes core infrastructure services such as DNS, DHCP, NFS, Samba, and local user management.

---

## Architecture

- DNS: BIND (company.local)
- DHCP: automatic IP assignment
- NFS: Linux shared storage
- Samba: Windows/Linux file sharing
- Users: local RBAC model
- Security: SELinux + Firewalld

---

## Network Design

192.168.100.0/24 internal lab network

- Server: 192.168.100.10
- Clients: DHCP range 192.168.100.100–200

---

## Services

### DNS
BIND server resolving internal domain names.

### DHCP
Automatic IP provisioning for clients.

### NFS
Linux shared storage mounted on clients.

### Samba
SMB file sharing for Windows compatibility.

---

## Skills Demonstrated

- Linux system administration (RHEL)
- Network services configuration
- Security hardening (SELinux, firewall)
- Identity management (users/groups)
- Troubleshooting and logging

---

## Author
Amer Al Hasheesh
