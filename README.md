# homelab
My homelab and stuff.

Using Proxmox as a Hypervisor platform on a donated CPU.
Have not checked idle watt usage but its using Athlon 3000G, 16GB of DDR4 RAM, and 2 3TB HDDs.

Current services running:
- OMV - For personal cloud storage. Runs an isolated Caddy instance for private file sharing. File Browser Quantum for web UI. Previously used RAID1 but switched to local Rsync for backup rather than redundancy.
- Caddy - linked to local and DDNS'd with DuckDNS, need more research to do DNS01 challenge with local IP.  
- Zerotier - Private sharing and remote access. Might consider Pangolin or Tailscale, whichever is more convenient for sharing access with friends.
- PiHole - Network-wide local DNS and ad blocking. Might consider AdGuard Home or Technitium soon.
- Testing Services - for future use and integration.
- OpenWRT running on a TP-Link AX23, set with static IP leases for PC and server reservations.

Soon:
- Jellyfin - local media server.
- Some Web UI Dashboard for monitoring.
- Vaultwarden - migrating from BitWarden online.
- Wiredoor or some reverse proxy software, would buy a VPS as a front IP to proxy traffic from.
- ERPNext/Open-source ERP - business software learning for inventory and invoices for no initial cost.
- Things I have not thought about.


# Configs
Here is also the repo for my configuration files from Home Lab and my Personal Setup. Such as Window Manager, Terminal settings, notification and shell, waybar, etc.
