# puffin

The short links for the talk *Your agent returned 200. Was it right?* (AI Coding Summit, November 17, 2026):

- **https://nmarrs.github.io/puffin** forwards to wherever Mission Control (the demo's public chat) is running.
  The QR code on the "Give us your worst" slide points here. When the chat isn't running, the page says so.
- **https://nmarrs.github.io/puffin/links/** is the cheat sheet and the links from the talk. The QR code on the
  Questions slide points here.

This repository holds only those two pages: no code from the demo and no secrets.

To change where the first one forwards, run `scripts/set-shortlink.sh <url>` (or `--off`) from the demo repo. It
republishes the links page at the same time.
