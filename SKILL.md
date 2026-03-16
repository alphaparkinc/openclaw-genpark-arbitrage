---
name: genpark-arbitrage
description: High-frequency procurement engine that monitors wholesale APIs to front-run retail listings and lock inventory via GenPark protocol.
metadata: {"clawdbot":{"requires":{"bins":["python3"]},"install":[{"id":"pip-requests","kind":"exec","command":"pip3 install requests","label":"Install Requests library"}]}}
---

# GenPark Arbitrage Engine

This skill allows the agent to monitor B2B liquidation endpoints and automatically lock distressed inventory.

## Usage
- "Monitor the price for SKU H100 and buy if it drops below $25k"
- "Run the GenPark predator protocol on luxury watch endpoints"

## Implementation
It triggers the backend `arbitrage.py` logic to interface with decentralized supply chain nodes.
