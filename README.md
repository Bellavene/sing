# sing

A TUI panel to directly talk to [Sing-Box](https://github.com/SagerNet/sing-box) API calls using websocket connection for speed.

<img width="1650" height="752" alt="Screenshot 2026-09-26 at 02 37 33 2" src="https://github.com/user-attachments/assets/a062d5d1-9325-4394-b30e-4a707cfba220" />
<img width="1694" height="1128" alt="Screenshot 2026-09-24 at 14 13 59 2" src="https://github.com/user-attachments/assets/f804eb39-db11-432b-9b95-8deaaee1c69e" />

# Features

  1. Visually pleasant minimal design. Highlights problematic connections.
  2. AbuseIPDB API integration to fetch and cache instantly additional information about all IP’s
  3. A simple GEO tracking system for outgoing IP’s based on cached AbuseIPDB queries.

# Shortcuts

## Server version

Enter) Shows a popup with queried information about incomming and outgoing IP
K) Kills selected connection
C) Copies outgoing IP
Shift+C) Copies incomming IP
D )Copies domain name
Escape) Toggles Catch list
Tab) Adds current selection to Catch list
R) Toggles catching of outgoing connections by country code into the Catch list. (Default RU)
S) Changes sort order

## Client version

Enter) Shows a popup with queried information about outgoing IP
K) Kills selected connection
C) Copies outgoing IP
D) Copies domain name
S) Changes sort order

# Information
All settings can be set directly in the Python code.
Uses Hack Nerd Font for icons.
