# Sling

A quiet two-player physics strategy game. Three captures win.

- Two players, P2P over WebRTC (one data channel, no game server, no logins, no installs).
- Room codes are copy-paste: host generates one, friend pastes it, friend sends the reply back.
- Drag from your pad to aim, let go to launch. Bend your shot around two gravity wells.
- The physics is real: Newtonian gravitation, fixed-step integration at 60 Hz, deterministic on both peers — only the launch parameters travel, both sides agree on the outcome.
- The nonsense is labeled: "Low-Gravity Tuesday" and "The Purple Moon" each come with a what's-real explanation.

## How to play
1. One player clicks **Host a room** and sends the room code to the other.
2. The other clicks **Join a room**, pastes the code, and sends the reply back.
3. Host pastes the reply. Connected. Drag from your blue pad and let go.

Run locally: serve the folder over HTTP (`python3 -m http.server`) or open any static host.
