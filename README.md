# Ismail Opu — Portfolio

Personal portfolio of Ismail Opu, CS student at Brac University and full-stack developer. Live at **[ismailopu.is-a.dev](https://ismailopu.is-a.dev)**.

A single static page with a Three.js starfield you fly through as you scroll, sections that move in from 3D depth, cards that tilt toward the mouse, and a layout that works on phones.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts |
| `avatar.jpg` | Profile photo |
| `status.json` | Availability that every visitor sees: `{ "available": true }` or `false` |
| `CNAME` | Custom domain for GitHub Pages |

## Availability

Edit `status.json` and set `"available"` to `true` or `false`. The status dots, hero badge and contact banner all follow it.

Owner mode (click the **IO.** logo 5 times quickly, then enter the password) shows a switch that previews the other state **in your own browser only**.

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.
