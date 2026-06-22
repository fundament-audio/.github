# FUNDAMENT 

**Open-source, fully-measured loudspeaker design.**

Reference-level audio hardware that's documented, measurable, repairable, and reproducible - and stays that way. No black boxes.

---

## What this is

FUNDAMENT is a community-driven platform for open loudspeaker design, starting with subwoofers.

Good loudspeakers (especially serious subwoofers) are genuinely hard to get hold of in much of the world. The best references are excellent, but shipping heavy cabinets across borders, plus import duty, VAT, and no local warranty, makes them unrealistic for a lot of people. At the same time, brilliant DIY builds that measure extremely well are scattered across forums, then buried and forgotten.

FUNDAMENT exists to fix both: take known-good engineering, do it properly in the open, and keep the knowledge consolidated, validated, and buildable anywhere.

**The platform is the *method*. Each speaker is a *build* on top of it.**

## Principles

- **Open plans** -> enclosure drawings, cut lists, bracing, all of it.
- **Open DSP** -> the actual filter files (e.g. Hypex HFD), presets included. No secret tuning.
- **Published measurements** —> *and* the exact protocol used to take them, so results are comparable and reproducible.
- **Revision history** —> every change traceable.
- **Accessible parts** —> off-the-shelf drivers and amps, multiple suppliers, no single-vendor lock-in.
- **Repairable & upgradeable** —> by design.

> If it isn't documented, measurable, and reproducible, it isn't FUNDAMENT.

## How it's organised

- **This org** holds the shared platform: design conventions, the measurement protocol, DSP/protection methodology, documentation standards.
- **Each build is its own repo** — plans, BOM, DSP files, measurements for one speaker.

### Builds

| Build | What | Status |
|---|---|---|
| **[S18](https://github.com/fundament-audio/s18)** | Sealed 18″ reference subwoofer (BMS 18N862 + Hypex FA502) | 🟡 In progress —> Initial design phase |
| S15 | Sealed 15″ | ⚪ Concept |
| D12 | Dual-12″ force-cancelling sub | ⚪ Concept |
| M8C | 4×8″ active cardioid module (higher crossover, directivity-controlled) | ⚪ Concept |

## What "reference-level" means here

Precisely this: a reference *design*, validated by a *measured reference unit*, with a fixed published protocol so community builds are comparable.

What it does **not** mean: a guarantee that every home build is reference-grade. We can't certify a stranger's MDF, glue-up, or assembly — material and build variation is real and measurable. So the deal is transparency: published design, published measurements of the reference build, a repeatable protocol, and honest numbers with the raw data behind them.

Independent measurement (Klippel NFS / anechoic / ASR-style) is actively wanted — that's what turns "another open build" into something trustworthy.

## Measurement protocol

→ see **PROTOCOL.md** *(coming)*

Short version: groundplane + nearfield for the room-independent response, THD vs level, long-term thermal compression, and per-unit T/S verification - all to a fixed, published method so builds compare like-for-like.

## Contributing

- Build it, measure it to the protocol, share the data.
- Report issues, suggest revisions, open PRs against plans/DSP.
- Independent testing with proper gear is especially valued.
- Feel free to participate in the ASR (AudioScienceReview) discussions

See `CONTRIBUTING.md` in each build repo.

## Built-to-order (later)

For people who'd rather not cut cabinets and wire amps, hand-built-to-order units may be offered down the line - hand-built in Denmark. The core always stays open: plans, presets, measurements, and DSP files remain public, forever. Built-to-order is convenience, never a paywall around the knowledge.

## Licence

- **Hardware / designs:** CERN-OHL-S-2.0 (strongly reciprocal - derivatives stay open)
- **Documentation / measurements:** CC-BY-SA-4.0
- **Code / scripts:** MIT

---

*Let's build something nice together.*
