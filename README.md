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

### Personal Home Lab Infrastructure

<table>
  <thead>
    <tr>
      <th width="35%">Infrastructure Project</th>
      <th width="16%">Proof</th>
      <th width="30%">Purpose</th>
      <th width="18%">Stack</th>
      <th width="8%">Status</th>
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
      <td>Network Monitoring & Observability</td>
      <td>Coming soon</td>
      <td>SNMP and flow monitoring with alerting across all lab VLANs.</td>
      <td>TBD</td>
      <td><img src="https://img.shields.io/badge/Queued-lightgrey" alt="Queued"></td>
    </tr>
  </tbody>
</table>

### Simulated Client Engagement:
