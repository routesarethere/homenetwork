# Phase 7 — Garage Cameras, Home Automation & RetroPie

[← Back to README](../README.md)

---

## Phase 7a — Jan 2024

With a media server and capable media client sorted, I decided to shift focus to the detached garage. I wanted to install a camera, so I purchased a single Reolink 843A to start and had it write footage to my Synology NAS using one of the two included Surveillance Station licenses.

I also found out that MyQ garage door openers were no longer able to be used with Home Assistant, but a popular alternative — ratgdo — was. I purchased one for each garage door and was again impressed with how easy it was to install and connect up to Home Assistant.

It was super fun to nerd out on automations — auto-closing garage doors, notifications tuned to my exact liking. I could pull up one page and see the garage door status plus a live camera feed to confirm. Did I remember to close the garage door? ADHD and OCD, be gone.

I also wondered: could I make a fail-safe automation to turn off the Ecobee thermostat controlling the natural gas heater if the garage doors are open and won't close for some reason? Spoiler alert: I can, and I did.

---

## Phase 7b — Feb 2024

It had been about a month since I bought the RPi, and at this point all it was doing was running the secondary Pi-Hole instance while the primary ran in Proxmox on the Lenovo. What other fun projects can you do with a Pi?

I remembered emulating Pokémon games on school computers in high school, and I'd been enjoying an arcade bar with friends recently. How about a RetroPie console?

I'll admit — this was not as quick and easy as other things I'd done up to this point. Don't be like me: read the RetroPie docs carefully. Save yourself time and use the version of Raspbian they recommend (Buster). Regardless, it was worth the struggle to play Frogger, Donkey Kong, and Pokémon from the couch.

---

*Previous: [Phase 6 — Proxmox & The NAS](phase-6.md)*
*Next: [Phase 8 — OLED TV, Plex & Better Security](phase-8.md)*
