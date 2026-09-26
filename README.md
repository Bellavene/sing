## sing

A TUI panel for [Sing-Box](https://github.com/SagerNet/sing-box)’s API calls using websocket connection for speed. Seperate versions for sing-box running on a server and on a client

<img width="1650" height="752" alt="Screenshot 2026-09-26 at 02 37 33 2" src="https://github.com/user-attachments/assets/a062d5d1-9325-4394-b30e-4a707cfba220" />
<img width="1694" height="1128" alt="Screenshot 2026-09-24 at 14 13 59 2" src="https://github.com/user-attachments/assets/f804eb39-db11-432b-9b95-8deaaee1c69e" />

## Features

  1. Visually pleasant minimal design.
  2. Highlights problematic connections and outgoing IP’s to specific country code.
  3. AbuseIPDB API integration to fetch and cache instantly additional information about all IP’s
  4. A simple GEO tracking system for outgoing IP’s based on cached AbuseIPDB queries.

### Shortcuts for the server version

- <b>Enter</b>  Shows a popup with queried information about incomming and outgoing IP
- <b>Escape</b>  Toggles Catch list
- <b>Tab</b>  Adds current selection to Catch list
- <b>R</b>  Toggles catching of outgoing connections by country code into the Catch list. (Default RU)
- <b>K</b>  Kills selected connection
- <b>C</b>  Copies outgoing IP
- <b>Shift+C</b>  Copies incomming IP
- <b>D</b>  Copies domain name
- <b>S</b>  Changes sort order

### Shortcuts for the client version

- <b>Enter</b>  Shows a popup with queried information about outgoing IP
- <b>Escape</b>  Opens outbound proxy selector
- <b>K</b>  Kills selected connection
- <b>C</b>  Copies outgoing IP
- <b>D</b>  Copies domain name
- <b>S</b>  Changes sort order

### Information
All settings, API address and keys can be set directly in the Python code.
Uses Hack Nerd Font for icons.
