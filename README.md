🎮 CS2 Discord RPC by Chmieluuu

A lightweight and safe Discord Rich Presence app for Counter-Strike 2.
It automatically displays your current in-game status on Discord — showing your map, game mode, side (CT / T), and live score in real time — all without breaking Steam or VAC rules.

✨ Features

🟢 Live Discord Status – Automatically shows map, game mode, team side (CT / T), and score.

🗺️ Dynamic Map & Team Icons – Large map icon with tooltip, small CT / T icon matching your current side.

⚙️ Automatic Setup – Creates gamestate_integration_cs2_rpc.cfg automatically on first launch.

💬 System Tray Integration – Runs in the background with notifications and quick-access menu.

🌍 Multilingual Interface – Supports Polish 🇵🇱, English 🇬🇧, and Russian 🇷🇺.

🔒 100% Safe – Uses Valve’s official Game State Integration (no memory reading, no injection, no overlay).

🧩 How It Works

The app listens for JSON data from CS2’s Game State Integration (GSI).

It parses map, mode, team, and score, then updates your Discord Rich Presence through the official Discord API.

Everything happens locally — fully compliant with Steam / VAC policies.

💾 Installation & Usage

Download the latest .exe file from the Releases
 page.

Run CS2DiscordRPC.exe (Discord must be open).

Launch Counter-Strike 2 — your Discord profile will automatically display:

the map you’re playing on,

your team side (CT / T),

current score,

and match type (Competitive, Wingman, etc.).

🖼️ Discord Developer Setup

If you want to customize icons:

Go to Discord Developer Portal
.

Create an application and upload images under Rich Presence → Art Assets.

Use map names like de_mirage, de_inferno, de_nuke, etc.

Set small icons: ct and t.

🧠 Credits: https://github.com/Chm1eluuu/CS2-Discord-RPC

Made with ❤️ by Chmieluuu
GitHub Repository
