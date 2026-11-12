# PDragonLabs · Schumann Resonance

Live view of Earth’s electromagnetic heartbeat — the Schumann Resonance.

**Live page:** [https://pdragonlabs.github.io/schumann/](https://pdragonlabs.github.io/schumann/)

## What this is

A lightweight GitHub Pages site that embeds the MeteoAgent Schumann Resonance widget and adds a clear scientific overview, standard mode frequencies, and links to primary public data sources.

The original page was a bare iframe. This version gives it a proper room: context, frequencies, and sources so the live reading sits inside something readable.

## Schumann Resonance (short version)

The Earth and the lower ionosphere form a natural electromagnetic cavity. Global lightning (roughly 50 strikes per second) continuously excites standing waves inside it.

The fundamental mode is commonly observed near **7.83 Hz**, with harmonics near:

| Mode | Approximate frequency |
|------|------------------------|
| 1    | 7.83 Hz               |
| 2    | 14.3 Hz               |
| 3    | 20.8 Hz               |
| 4    | 27.3 Hz               |
| 5    | 33.8 Hz               |

These are not fixed constants. They shift with ionospheric height, conductivity, day/night cycle, season, and geomagnetic activity. The signal is extremely weak (picotesla range).

Primary public measurement source widely referenced online is the Space Observing System at Tomsk State University (Russia).

## What’s on the page

- Embedded MeteoAgent Schumann card (live status + recent history)
- Brief explanation of the cavity resonance
- Standard mode frequency reference
- Links to Tomsk, HeartMath Global Coherence Monitoring System, and other public dashboards
- PDragonLabs footer (Station and related work)

## Deploy / update

1. This repo is already set up for GitHub Pages from the `main` branch (root).
2. Edit `index.html` (or this README).
3. Push to `main`.
4. The site at https://pdragonlabs.github.io/schumann/ updates within a minute or two.

To change the embedded widget, replace the iframe `src` in `index.html`. The current source is the public MeteoAgent card endpoint.

## Files

- `index.html` — the live page
- `README.md` — this file

## Related

- [PDRAGONLABS Station](https://pdragonlabs.github.io/station/) — SoundCloud room
- [GitHub](https://github.com/PDragonLabs)
- [Linktree](https://linktr.ee/pdragonlabs)

---

*PDragonLabs · Earth’s 7.83 Hz, in the room.*
