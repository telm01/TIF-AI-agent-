# PSP-Style Localhost Game UI

A lightweight PSP-inspired game launcher UI made with plain HTML, CSS and JavaScript.

## Run locally

### Option 1 — Python

Open a terminal in this folder:

```bash
python3 -m http.server 8080
```

Then open:

http://localhost:8080

### Option 2 — Node.js

```bash
npx serve .
```

## Raspberry Pi

To make it accessible from another device on your LAN:

```bash
python3 -m http.server 8080 --bind 0.0.0.0
```

Find the Raspberry Pi IP:

```bash
hostname -I
```

Then open:

```text
http://YOUR_PI_IP:8080
```

## Controls

- Left / Right arrows: change game
- Enter / Space: launch
- Mouse/touch: select game
