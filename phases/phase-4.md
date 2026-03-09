# Phase 4 — New Firewall

[← Back to README](../README.md)

---

## Phase 4 — Jan 2023

Time for a new firewall. I debated for hours between many options, factoring in my future plans for security cameras. Ubiquiti is appealing — the UDM Pro can run Protect — but the price per camera is too much. I decided to stay away from Ubiquiti for everything except wireless and go with an OPNsense firewall instead.

I didn't have any spare hardware to run it on, so I debated between a Qotom from Amazon or the slightly pricier Protectli. I ended up opting for the better customer support and warranty and got a Protectli FW4B. Protectli lets you choose an optional coreboot BIOS, which they'll preinstall and verify along with your choice of OS — OPNsense in my case.

It was super easy to get set up, build out my VLANs, and get firewall rules in place. I can now enjoy an Open NAT type for Xbox Live gaming — it was Strict with the SRX, which had been driving me crazy.

---

*Previous: [Phase 3 — The Basement Rack](phase-3.md)*
*Next: [Phase 5 — Raspberry Pi & Home Assistant](phase-5.md)*
