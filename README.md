# AirTor

AirTor is dedicated to facilitating truly decentralized anonymous web-traffic. A blockchain architecture built on top of the ideas of The Onion Router (ToR), AirTor combines TOR routers and TOR relays with physically independent communication to create an entirely separate, self-sustaining anonymous internet protocol.

## Setup 

The initial AirTor protocol will be immediately interoperable with the existing ToR network, and any long-running ToR node is eligible to receive ATOR rewards for uptime within the active ToR network. Broad steps for existing ToR nodes are as follows:

- Nodes can identify themselves on our upcoming dashboard
- Nodes can then whitelist their current IP address to register into ATOR, with an ERC20 address to receive rewards
- Nodes will run our (web2) script alongside their existing packet management that communicates to our central (on-ToR!) server

In our transition to a truly independent internet protocol, the initial steps are:
- Addition of Nostr Protocol to relay nodes
- Transition from an ERC20 contract with a limited pool of reward tokens onto a dedicated blockchain where the gas-token is the one mined for Proof-of-Uptime
- The introduction of our dedicated mdoe, relay and router that will be operable both with the Web2 ToR and LoRa longwave radio communication



