# Phase 8 — OLED TV, Plex & Better Security

[← Back to README](../README.md)

---

## Phase 8a — Feb 2025

After buying a bunch of David Attenborough documentaries in 4K and ripping them to the server, I decided it was time to get a modern TV to actually enjoy all the benefits of my labor and the high quality uncompressed media I'd acquired. After researching extensively, I went out and got an LG C4 OLED 65". I can't believe it took me this long to experience the OLED goodness.

I also was not prepared for how much storage I was going to need storing everything in 4K.

A few people expressed interest in accessing my media library, so I started looking into Plex — it has some key features that make it a bit more user-friendly for sharing. I didn't want to just port-forward Plex openly to the world, so I only allowed my one friend's IP and used him as a test subject for remote playback.

I also got a convenient offer to bump my Spectrum plan from 600/20 to 1000/40 for a good deal. Forty Mbps upload works, but I really wish I could get symmetrical speeds to allow for more direct play and less transcoding.

---

## Phase 8b — Feb 2025

If I want to open things up to more friends and family, I needed to study up on securing things better.

I started by purchasing a Beelink Mini S12 Pro — a very popular choice for running Plex, as it has an N100 CPU with an Intel iGPU capable of handling several hardware transcoding streams simultaneously. A nice improvement for end users, and it pairs well with a 40 Mbps upload speed.

I fired up a bare metal install of Ubuntu on the Beelink and put it on its own VLAN, only allowing it to reach the NAS. Using Docker, I spun up Plex and a reverse proxy solution called SWAG that automatically handles certificates and DDNS. With all that in place, I enabled the port forward for the reverse proxy and invited a few more people to use Plex.

---

*Previous: [Phase 7 — Garage Cameras, Home Automation & RetroPie](phase-7.md)*
*Next: [Phase 9 — The *arr Stack](phase-9.md)*
