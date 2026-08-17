<div align="center">

# Chibuike "BK" Okerulu

*Network & Cloud Engineering | CompTIA Network+ Certified | Atlanta, GA*

[LinkedIn](https://www.linkedin.com/in/chibuike-okerulu/)

</div>

---

> ### Portfolio Note
>
> The projects here are built to mirror the actual work of a network or cloud network engineer running hybrid infrastructure. That means VLAN design, inter-VLAN routing and firewall rules, DHCP and DNS, hypervisor administration, self-managed Active Directory, and connecting on-prem gear to **Microsoft Azure**.
>
> This is not a cloud trial walkthrough. The lab runs on real hardware: a MikroTik router I configure entirely from the CLI, a managed switch, and a Proxmox host. I document every build the way I would document a production change, including what broke along the way and how I fixed it.

---

## Network & Cloud Infrastructure

<table>
  <thead>
    <tr>
      <th width="35%">Infrastructure Project</th>
      <th width="16%">Proof</th>
      <th width="28%">Purpose</th>
      <th width="16%">Stack</th>
      <th width="10%">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/the-buike/homelab-lab">Hybrid Home Lab: Core Build</a></td>
      <td>Configs & Screenshots Included</td>
      <td>The physical foundation of the lab. Router, managed switch, hypervisor host, and secure remote access over an overlay network.</td>
      <td>MikroTik RouterOS · Proxmox VE · Ubuntu Server · Tailscale</td>
      <td><img src="https://img.shields.io/badge/In%20Progress-blue" alt="In Progress"></td>
    </tr>
    <tr>
      <td><a href="https://github.com/the-buike/homelab-lab">VLAN Segmentation & Inter-VLAN Firewall</a></td>
      <td>CLI Configs Included</td>
      <td>Splits the lab into Management, Services, and DMZ VLANs, each with its own DHCP pool and firewall rules controlling traffic between zones.</td>
      <td>MikroTik RouterOS · 802.1Q · DHCP</td>
      <td><img src="https://img.shields.io/badge/Complete-2ea44f" alt="Complete"></td>
    </tr>
    <tr>
      <td><a href="https://github.com/the-buike/Active-Directory">Active Directory Domain Services Lab</a></td>
      <td>Screenshots Included</td>
      <td>A Windows Server 2022 VM promoted to domain controller, with an OU structure and DNS set up for the lab domain.</td>
      <td>Windows Server 2022 · AD DS · DNS · Proxmox</td>
      <td><img src="https://img.shields.io/badge/Complete-2ea44f" alt="Complete"></td>
    </tr>
    <tr>
      <td><a href="https://github.com/the-buike/Enterprise-Simulation">Enterprise Simulation: Ashgrove Regional Medical Center</a></td>
      <td>Coming per phase</td>
      <td>A full hybrid environment for a fictional hospital network. Department VLANs and switching in EVE-NG, connected to self-managed AD DS in Azure over a site-to-site VPN, with department-based access control modeled on real healthcare IT practices.</td>
      <td>EVE-NG · Azure VNets · VPN Gateway · Windows Server 2022</td>
      <td><img src="https://img.shields.io/badge/In%20Progress-blue" alt="In Progress"></td>
    </tr>
    <tr>
      <td>
        <strong>osTicket (Help Desk Ticketing System)</strong><br>
        &#9702; <a href="https://github.com/the-buike/osTicket---Ashgrove-Clinic-Configuration">Prerequisites and Installation</a><br>
        &#9702; <a href="https://github.com/the-buike/osTicket---Ashgrove-Clinic-Configuration">Post-Installation Configuration</a><br>
        &#9702; <a href="https://github.com/the-buike/osTicket---Ashgrove-Clinic-Configuration">Ticket Lifecycle Examples</a>
      </td>
      <td>Configs, Screenshots & Ticket Writeups</td>
      <td>A clinical IT help desk for Ashgrove Regional Medical Center — server prep, department/SLA configuration, and real ticket workflows from open to resolution.</td>
      <td>osTicket · PHP · MySQL/MariaDB · Apache</td>
      <td><img src="https://img.shields.io/badge/In%20Progress-blue" alt="In Progress"></td>
    </tr>
    <tr>
      <td>Network Monitoring & Observability</td>
      <td>Coming soon</td>
      <td>SNMP and flow monitoring with alerting across all lab VLANs.</td>
      <td>TBD</td>
      <td><img src="https://img.shields.io/badge/Queued-lightgrey" alt="Queued"></td>
    </tr>
  </tbody>
</table>

---

## Certification Study Tools (Built, Not Just Studied)

| Project | Proof | Purpose | Stack | Status |
|---|---|---|---|---|
| [Network+ Quiz PWA](https://the-buike.github.io/Net-Plus/) | Live App | A 100-question quiz app weighted to match the N10-009 exam blueprint. I built it for my own prep and passed with an **810**. | JavaScript · PWA · GitHub Pages | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |
| CCNA 200-301 Prep PWA | Live App | 150 questions and 80 flashcards covering all six CCNA exam domains. | JavaScript · PWA · GitHub Pages | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |

---

## Data & Analytics Background

| Project | Purpose | Stack | Status |
|---|---|---|---|
| E-Commerce Analytics Portfolio | Customer segmentation, market basket analysis, and dashboards built on synthetic retail data. From my earlier BI work, and still useful for reporting and monitoring today. | Python · SQL · Power BI | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |

---

## Certifications

| Certification | Status |
|---|---|
| CompTIA Network+ (N10-009), scored **810** | ![Earned](https://img.shields.io/badge/Earned-2ea44f) |
| Microsoft Azure Administrator (AZ-104) | ![In Progress](https://img.shields.io/badge/In%20Progress-blue) |
| Cisco CCNA (200-301) | ![Queued](https://img.shields.io/badge/Queued-lightgrey) |

---

## Skills Snapshot

**Networking:** VLANs & 802.1Q · Inter-VLAN routing · Firewall policy · DHCP/DNS · NAT · Subnetting · OSPF/BGP concepts · Site-to-site VPN · MikroTik RouterOS CLI

**Cloud & Systems:** Azure (VNets, VMs, VPN Gateway) · Proxmox VE · Windows Server 2022 · AD DS · Ubuntu Server · Tailscale · SSH

**Scripting & Data:** Python · SQL · PHP/Laravel · JavaScript · Power BI

---

<div align="center">

📫 **bukkyokerulu@gmail.com** · 🌐 [Portfolio](#) <!-- update -->

*A non-linear path, all of it pointing toward infrastructure.*

</div>
