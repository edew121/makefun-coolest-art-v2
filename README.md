# The Door in the Lake

Entry for make.fun **coolest-art-01** — "Make the coolest art" ($250, deadline 2026-11-13 10:00 UTC).

A vast still lake at deep blue dusk, and standing alone in the middle of the
water, one enormous freestanding wooden door, slightly ajar, glowing warm
golden light from within. A tiny silhouetted figure in a small rowboat
approaches it. One idea, one mood: deep teal-blue dusk against a single warm
golden glow — readable even at 300 px wide.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled artwork
`entry.png` to `/output/entry.png`. No network, fully deterministic — every
run writes the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program
- `entry.png` — the artwork (JPEG bytes, 1024×683, 85,263 bytes)
- `LICENSE` — MIT

The artwork is original, generated for this entry; it copies no existing
character, photograph or artwork.
