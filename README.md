<div align="center">

```
██████╗ ██╗      █████╗ ██████╗ ███████╗
██╔════╝ ██║     ██╔══██╗██╔══██╗██╔════╝
██║  ███╗██║     ███████║██████╔╝█████╗  
██║   ██║██║     ██╔══██║██╔══██╗██╔══╝  
╚██████╔╝███████╗██║  ██║██║  ██║███████╗
 ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
          ██████╗██╗     ██╗███████╗███╗   ██╗████████╗
         ██╔════╝██║     ██║██╔════╝████╗  ██║╚══██╔══╝
         ██║     ██║     ██║█████╗  ██╔██╗ ██║   ██║   
         ██║     ██║     ██║██╔══╝  ██║╚██╗██║   ██║   
         ╚██████╗███████╗██║███████╗██║ ╚████║   ██║   
          ╚═════╝╚══════╝╚═╝╚══════╝╚═╝  ╚═══╝   ╚═╝  
```

<img src="https://img.shields.io/badge/STATUS-UNDETECTED-cc0022?style=for-the-badge&labelColor=0a0000&color=cc0022" />
<img src="https://img.shields.io/badge/VERSION-2.0-cc0022?style=for-the-badge&labelColor=0a0000" />
<img src="https://img.shields.io/badge/AUTHOR-GLARINGLY-8b0000?style=for-the-badge&labelColor=0a0000" />
<img src="https://img.shields.io/badge/PLATFORM-BLOOKET-cc2200?style=for-the-badge&labelColor=0a0000" />

<br/>

> **The #1 Blooket cheat GUI. Dark. Fast. Untouchable.**

<br/>

```
╔══════════════════════════════════════════════════════╗
║  ⚠  USE AT YOUR OWN RISK  //  FOR EDUCATIONAL USE   ║
╚══════════════════════════════════════════════════════╝
```

</div>

---

## `// WHAT IS GLARE CLIENT`

**Glare Client** is a **premium Blooket cheat GUI** built from the ground up by [Glaringly](https://github.com/Glaringly). It's not a script, it's a full client. Dark red neon interface. Buttery animations. Ripple effects. Scanlines. Corner decorations. Toast notifications. Every detail obsessed over.

This is what a **#1 cheat GUI** looks like.

---

## `// FEATURES`

### 🎮 Global Cheats
| Feature | Description |
|---|---|
| **Auto Answer** | Instantly clicks the correct answer the moment a question loads |
| **Spam Answer** | Floods answers for maximum speed |
| **Show Answers** | Reveals all correct answers on-screen |

### 🏴‍☠️ Game Mode Cheats
> Pirate's Voyage · Gold Quest · Cafe · Crypto Hack · Deceptive Dinos · Tower Defense 1 & 2 · Factory · Fishing Frenzy · Flappy Blook · Tower of Doom · Crazy Kingdom · Racing · Battle Royale · Blook Rush · Monster Brawl · Santa's Workshop

Each game mode has its own dedicated cheat set — tokens, gold, XP, instant wins, godmode, and more.

### 👑 Host Tools
- Kick players
- Flood questions
- Lock lobbies
- Mass manipulate game state

### 🔔 Alerts System
- Real-time activity log
- Cheat report blocker (blocks Blooket's RC endpoint)
- Timestamped events

### ⚙️ Settings
- Full theme customization (colors, backgrounds, buttons)
- Custom keybinds for hide/close
- GUI scale slider
- Persistent settings saved to `localStorage`

---

## `// THE GUI`

```
┌────────────────────────────────────────────────────┐
│  GLARE                    [ CTRL+E to hide ]  [─][✕]│
│  CLIENT                                             │
│  ──────────                                         │
│  by Glaringly                                       │
│  ▸ GITHUB   ├──────────────────────────────────────┤
│             │                                       │
│  ALERTS     │   ┌─ GLOBAL // CHEATS ──────────────┐ │
│  GLOBAL ◄   │   │                                 │ │
│  HOST       │   │  [ AUTO ANSWER ]  [ SPAM ]      │ │
│  GOLD QUEST │   │  [ SHOW ANSWERS ] [ TOKENS ]    │ │
│  CAFE       │   │                                 │ │
│  CRYPTO     │   └─────────────────────────────────┘ │
│  RACING     │                                       │
│  ...        │                                       │
└────────────────────────────────────────────────────┘
```

**Animations include:**
- 🔴 Entry slide-up fade on open
- 🔴 Staggered card reveal when switching tabs  
- 🔴 Ripple burst on button click
- 🔴 CRT scanline sweep effect
- 🔴 Crimson corner bracket blinks
- 🔴 Logo flicker (CRT style)
- 🔴 Toast notifications on every action
- 🔴 Hover shimmer on cheat cards
- 🔴 Neon left-edge indicator on nav hover

---

## `// INSTALLATION`

### Method 1 — Bookmarklet
1. Copy the contents of `GlareClient.js`
2. Create a new bookmark in your browser
3. In the URL field, paste:
```
javascript: /* paste GlareClient.js contents here */
```
4. Navigate to [blooket.com](https://blooket.com) and click the bookmark

### Method 2 — Console Injection
1. Open Blooket and join a game
2. Press `F12` → go to **Console**
3. Paste the contents of `GlareClient.js` and hit `Enter`

### Method 3 — Tampermonkey
1. Install [Tampermonkey](https://www.tampermonkey.net/)
2. Create a new script
3. Paste `GlareClient.js` contents
4. Set `@match` to `https://www.blooket.com/*`
5. Save and refresh

---

## `// KEYBINDS`

| Keybind | Action |
|---|---|
| `Ctrl + E` | Toggle GUI visibility |
| `Ctrl + X` | Quick disable all cheats + close |

> Both keybinds are fully customizable in the Settings tab.

---

## `// FILE STRUCTURE`

```
Glare-Client/
│
├── Gui/GlareClient.js          ← The entire client (single file)
└── README.md       ← You are here
```

---

## `// TECH STACK`

```
Vanilla JavaScript  ──  No dependencies. No frameworks. Pure JS.
CSS Animations      ──  Keyframe-driven. 9 custom animations.
Orbitron            ──  Headers / Logo
Rajdhani            ──  Navigation / Buttons  
Share Tech Mono     ──  Inputs / Hints / Code
LocalStorage API    ──  Persistent settings
Web Animations API  ──  Entry + stagger animations
```

---

## `// CREDITS`

<div align="center">

| | |
|---|---|
| **Built by** | [Glaringly](https://github.com/Glaringly) |
| **Version** | 1.0 |

</div>

---

## `// DISCLAIMER`

```
╔════════════════════════════════════════════════════════════╗
║                                                            ║
║   Glare Client is made for educational purposes only.      ║
║   Using cheats in online games may violate Terms of        ║
║   Service. The developer is not responsible for any        ║
║   account bans, suspensions, or consequences.              ║
║                                                            ║
║   You run this at your own risk.                           ║
║                                                            ║
╚════════════════════════════════════════════════════════════╝
```

---

<div align="center">

**⭐ Star the repo if Glare Client is #1 to you.**

<br/>

```
made with  🔴  by glaringly
```

</div>
