# P2P-Chat-Tester-Peerjs

A minimal peer-to-peer (P2P) chat tester built with PeerJS and plain HTML/JavaScript. This repository contains a simple front-end (HTML/CSS/JS) to test P2P connections and messaging between browser peers.

## Features

- Establish P2P connections using PeerJS
- Send and receive text messages between peers
- Simple, dependency-free HTML demo (no build step required)

## Prerequisites

- A modern web browser (Chrome, Firefox, Edge)
- (Optional) A local web server to serve files (recommended for some browser security restrictions). For quick testing you can use Python's simple server:

  - Python 3: `python -m http.server 8000`
  - Then open `http://localhost:8000` in your browser

## Usage

1. Clone or download this repository to your machine.
2. Serve the files with a local web server or open the `index.html` file directly in your browser.
3. Open the demo in two browser windows or on two devices. Each instance will have a PeerJS-generated ID.
4. Enter the remote peer's ID and connect. Once connected you can exchange text messages.

## File structure

- `index.html` — Main demo page with chat UI and PeerJS integration
- `README.md` — This file

## Contributing

Contributions and improvements are welcome. Open an issue or submit a pull request with your changes.

## License

This project is provided under the MIT License. See the LICENSE file if present.
