# NotGitServer
My own github running on my own server.

## Specifications
1. Running on a RISC-V star64 board.
2. Running Debian as its operating system.

## Network
Cloudflare Tunnel instead of port-forwarding.
- SSH/HTTPS access
- Dynamic DNS (DDNS) for remote access if no static IP (use DuckDNS, No-IP)
- Port forwarding from your home router (ports 22, 80, 443)
- Optionally set up NGINX or Caddy as a reverse proxy for HTTPS
