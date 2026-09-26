# Dimitris Papastamatis

Python, Linux and networking. Working toward AI infrastructure / platform engineering: taking servers and networks and turning them into reliable systems that other software depends on.

[dimitrispapastamatis.com](https://dimitrispapastamatis.com)

## Now

- Working through the infrastructure stack one layer a month, from networking and Linux up to Kubernetes, GPU model serving and hardening, and writing each layer up in [Homelab](https://github.com/offby1n/Homelab).
- IT support for a local business: their network, and whatever else stops working.

## What I run

- **Homelab:** a Dell R630 on Proxmox, with OPNsense as the firewall and Debian VMs for a database and testing.
- **An AI agent team:** four self-hosted Hermes Agent bots. I message one on Telegram, and it hands health checks and small admin jobs on the lab to the others. [Write-up](https://github.com/offby1n/Homelab/blob/main/writeups/hermes-agent-team.md)
- **[subnetlab.dev](https://subnetlab.dev):** a public subnet / VLSM calculator on AWS EC2, behind Cloudflare, with nginx and Let's Encrypt. The server only accepts web traffic from Cloudflare. The hosting is the project; the page itself is AI-generated.
- **Daily driver:** Arch Linux.

## What's in these repos

Command-line tools for networking, monitoring and security work, written in Python. Standard library by default — a third-party package only when learning that package is the point. Finished tools ship with an installer script and versioned releases, and every repo's README covers what it does and how to run it.

## How I work

- I learn by building tools I actually use, then running them for real.
- One new concept per project, layered on the ones before it, so the fundamentals become automatic.
- Infrastructure builds get a public write-up: what broke, how I found the cause, and what I'd do differently.
- Code is hand-written unless a repo's README says otherwise.

## Credentials

- PCEP — Certified Entry-Level Python Programmer, Python Institute (2026)
- Cambridge English C1
