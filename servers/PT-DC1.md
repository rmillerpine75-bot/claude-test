# PT-DC1 Server Documentation

**Generated:** 2026-02-03  
**Author:** Claude Desktop MCP

---

## Overview

| Property | Value |
|----------|-------|
| **Hostname** | PT-DC1 |
| **Domain** | PT.local |
| **Role** | Domain Controller (Primary) |
| **Location** | Default-First-Site-Name |

---

## Hardware

| Component | Specification |
|-----------|---------------|
| **Manufacturer** | Dell Inc. |
| **Model** | PowerEdge R240 |
| **CPU** | Intel Xeon E-2124 @ 3.30GHz |
| **CPU Cores** | 4 cores / 4 threads |
| **RAM** | 15.85 GB |

---

## Storage

| Drive | Total | Free | % Free |
|-------|-------|------|--------|
| C: | 446.5 GB | 420.72 GB | 94.2% |

---

## Network

| Property | Value |
|----------|-------|
| **IP Address** | 192.168.22.62 |

---

## Operating System

| Property | Value |
|----------|-------|
| **OS** | Windows Server 2022 Standard Evaluation |
| **Version** | 10.0.20348 |
| **Last Boot** | 2026-02-03 |

---

## Installed Roles

- Active Directory Domain Services
- DHCP Server
- DNS Server
- File and Storage Services

---

## Domain Controller Details

| Property | Value |
|----------|-------|
| **Global Catalog** | Yes |
| **AD Site** | Default-First-Site-Name |

---

## Notes

- Server is running evaluation license - plan for production licensing
- Single disk configuration - consider adding redundancy for production
- DHCP and DNS co-located on DC (common for small environments)
