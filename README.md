# Hybrid Ludo

A modern web-based implementation of the classic Ludo board game designed to bridge local and remote play. **Hybrid Ludo** allows players sitting together to share a single device while seamlessly connecting remote players to the exact same match.

---

## Key Features

* **Hybrid Multiplayer:** Support for pure local pass-and-play, online multiplayer, or a combined hybrid setup (e.g., 2 players on 1 local device + 1 online player).
* **Peer-to-Peer Networking:** Powered by PeerJS (WebRTC) for direct browser-to-browser communication. No external backend or database required.
* **Zero Dependencies / Single File:** Built into a fully self-contained `index.html` file containing all HTML, CSS, JavaScript, and game logic for effortless hosting on services like GitHub Pages.
* **Full Ludo Ruleset:** Includes common path traversal, private home columns, safe star spaces, token capture logic, extra turns on rolls of 6 or captures, and turn forfeiture rules.

---

## How to Play

### Modes

1. **Local Only:** Pass-and-play on a single shared screen (2 to 4 players).
2. **Host a Room:** Set up a match, pick how many local seats to keep on your device, and open the remaining seats for remote connections. Share the generated **Room Code** with off-site players.
3. **Join a Room:** Enter the Room Code provided by the host to connect directly to their game instance.

---

## Tech Stack

* **Frontend:** HTML5, CSS3 (Grid & Flexbox), Vanilla JavaScript
* **Networking:** [PeerJS](https://peerjs.com/) (WebRTC)
* **Hosting:** Optimized for static hosts (GitHub Pages, Netlify, Vercel)

---

## Local Setup

1. Clone or download this repository.
2. Open `ludo.html` directly in any web browser, or serve it using VS Code's **Live Server** extension.
