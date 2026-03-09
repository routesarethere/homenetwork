# Phase 11 — Proxmox Cluster

[← Back to README](../README.md)

---

## Phase 11 — Jan 2026

I really wanted to update Proxmox from 8.x to 9.x, but was worried that if something broke I'd feel stressed and rushed to fix it — I've become rather reliant on my self-hosted services, especially Home Assistant and the \*arr stack.

The only sensible thing to do was get a second Lenovo M920Q so I could update more safely and with minimal downtime.

I installed Proxmox 9.x on the new Lenovo and restored backups of all my VMs and LXCs. Thankfully, nothing broke. I did a fresh install of Proxmox 9.x on the original Lenovo for good measure and to make sure both systems were in good shape to become a cluster. Joining them together was super simple.

I also set up the RPi as a Qdevice to have quorum, should I ever want to set up HA for any services. For now, manually migrating is totally fine. I run everything on the original Lenovo except the \*arr stack, which now lives on the newer one — that way big, heavy downloads don't impact other services.

---

*Previous: [Phase 10 — Interior Cameras & New AP](phase-10.md)*
*Next: [Phase 12 — New Switch & Bigger Rack](phase-12.md)*
