# Phase 2 — Point-to-Point Link & The Switch Hunt

[← Back to README](../README.md)

---

## Phase 2a — Dec 2022

I mounted two Ubiquiti UISP LiteBeam 5AC units — one in the attic of the house, one in the attic of the garage. The LiteBeams typically need to be mounted outside with clear line-of-sight, but in this case the distance between the two buildings is only about 40 feet and it works great — 330 Mbps / 330 Mbps throughput. I used PVC conduit to mount them cleanly.

Once I verified connectivity at the garage switch, I mounted up a Ubiquiti AC-LR. The AP adopted to my existing site and boom — I had wireless in the garage! Besides the cable fishing headaches from Phase 1, it all seemed almost too easy.

---

## Phase 2b — Dec 2022

The noise from the basement travels easily up to the 2nd story, so I needed to find a switch that was quiet but also had enough PoE budget for my needs — rack mountable was a bonus.

Ubiquiti falls short on PoE budget. I picked up a Juniper EX2200 for $60 off eBay for the garage, but it was too loud to run in the basement. Back to eBay — I ordered a Juniper EX2200-C. Oops, not PoE. Cancel, order the PoE version. Fanless? Yes. High-pitched squeal? Also yes. Returned.

Juniper and Ubiquiti weren't going to cut it. All I really needed was a PoE switch that could do VLANs and had enough ports. I ordered a TP-Link SG1016PE and it works great.

---

*Previous: [Phase 1 — Wiring the House](phase-1.md)*
*Next: [Phase 3 — The Basement Rack](phase-3.md)*
