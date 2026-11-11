# Velvet North Blackjack — No-server setup

This is a static website version. It does not require you to create, deploy, or maintain your own Node.js server, hosting account, database, or backend project.

## Publish on GitHub Pages
1. Open the GitHub repository where you want the game.
2. Upload `index.html`, `style.css`, `game.js`, and this README into the repository's published root (not inside an extra nested folder).
3. In GitHub, open Settings → Pages and enable deployment from your main branch and root folder.
4. Open the Pages URL.

## Play with friends
1. The host opens the published game, enters their name and a room code, then taps **Create table**.
2. The host keeps that browser tab open and shares the Pages URL and room code in the group chat.
3. Each friend opens the same URL, enters a name and the exact same code, then taps **Join table**.
4. Everyone places a bet. The host taps **Start round**.
5. Players use Hit, Stand, and Double on their own devices.

## Important limitations — please read
- No personal server or backend project is needed. PeerJS's publicly hosted signaling service is used to establish direct browser-to-browser connections. This external service is still a dependency; no internet multiplayer can work with absolutely no network service of any kind.
- The host's phone is the table controller. It must stay online, keep the game tab open, and ideally keep the screen awake during play. If the host closes the page or loses connection, the table ends.
- This uses direct peer-to-peer data connections. Network/firewall/browser restrictions can prevent some players connecting. It is not guaranteed to work on every carrier or Wi-Fi network.
- A maximum of 12 players includes the host.
- Each player receives 250,000 virtual chips when joining. Balances last only for the current hosted table and are not saved after it ends.
- This is casual virtual-chip play only; no deposits, withdrawals, or real-money prizes.
- Do not use sensitive/private information as a room code. Room codes are not authentication or encryption for the game itself.
- This is a friends-only prototype, not a hardened production gambling platform.
- The mood is an original northern-night ambience, not a copy of the referenced song. No copyrighted music is bundled.
