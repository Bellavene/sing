# sing

A TUI panel for [Sing-Box](https://github.com/SagerNet/sing-box)’s API calls using websocket connection for speed.

<img width="1694" height="1128" alt="Screenshot 2026-09-24 at 14 13 59 2" src="https://github.com/user-attachments/assets/f804eb39-db11-432b-9b95-8deaaee1c69e" />

#### Features

  1. Visually pleasant minimal design.
  2. Highlights problematic connections.
  3. AbuseIPDB API integration to instantly fetch and cache additional information about all outbound and inbound IP’s
  4. A simple catching system for destination IP’s based on cached AbuseIPDB queries by country code.

Seperate versions for sing-box running on a server (sing) or local client machine (singlo)

#### Sing
<img width="1650" height="752" alt="Screenshot 2026-09-26 at 02 37 33 2" src="https://github.com/user-attachments/assets/a062d5d1-9325-4394-b30e-4a707cfba220" />

- <b>Enter</b>  Shows a popup with queried information about selected connection
- <b>Space</b>  Pauses list update
- <b>Escape</b>  Toggles Catch list
- <b>Tab</b>  Adds current selection to Catch list
- <b>R</b>  Toggles catching of destination IP’s by country code. (Default RU)
- <b>K</b>  Kills selected connection
- <b>C</b>  Copies destination IP
- <b>Shift+C</b>  Copies source IP
- <b>D</b>  Copies domain name
- <b>S</b>  Changes sort order

#### Singlo

<img width="876" height="386" alt="Screenshot 2026-09-26 at 05 40 15" src="https://github.com/user-attachments/assets/b20dbcd2-ec7d-409d-b920-6300f0bb45d9" />

- <b>Enter</b>  Shows a popup with queried information about destinaion IP
- <b>Space</b>  Pauses list update
- <b>Escape</b>  Opens outbound proxy selector
- <b>K</b>  Kills selected connection
- <b>C</b>  Copies destination IP
- <b>D</b>  Copies domain name
- <b>S</b>  Changes sort direction and sort order by most uploaded or downloaded.

#### Information
All settings, API address and keys can be set directly in the Python code.
Uses Hack Nerd Font for icons.
