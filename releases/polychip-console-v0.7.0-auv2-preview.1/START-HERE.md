# Polychip Console 0.7.0 — AUv2 preview 1

**GarageBand recognition remains unresolved.** The verified 0.7.0 AUv2 passes normal and out-of-process Audio Unit validation, but that does not establish GarageBand menu visibility or successful host use. Do not rely on this preview for an important project until you have tested your setup.

## What this download is

Instrument version: **0.7.0**. Download edition: **AUv2 preview 1 — documentation refresh**. This is a new immutable package of the existing verified AUv2 binary with corrected reader documentation, not new synth code or a new numeric instrument version.

Includes **Polychip Console.component (AUv2 only)** for macOS **12 or later**, Apple Silicon and Intel. No standalone app, AUv3, Windows or iOS build is included. This avoids mixing another installed/app version into this edition. The component is locally ad-hoc signed, **not Developer ID signed or notarized**.

## Sounds and controls

Six sources combine NES-style pulse, triangle and noise, Game Boy-style wave and pulse, and YM2612/OPN2-style FM. Each source has stereo placement and a send to shared echo. One shared LFO, a note/sustain envelope, four modulation routes and a resonant low/high/band-pass tone filter add movement.

ALL shows the six sources; MIX adjusts stereo placement and echo sends. MOD controls shared modulation, TONE controls the post-echo filter, and GB P focuses on the Game Boy pulse. The 32-cell Wave RAM editor shapes the Game Boy wave. Isolation controls and Panic remain available. This is an original behavioral subset, not full or cycle-accurate console emulation; no ROMs or game recordings are included.

The instrument retains 100 host parameters and the existing AU identity. Older saved states keep new sounds/effects muted or bypassed where needed; pre-0.7 patches load with Game Boy pulse muted. These are state-compatibility contracts, not a substitute for save/reopen testing in your host.

## Try it safely

1. Check macOS 12+ and quit music hosts before replacing a component. Back up any older component in a named folder **outside** scanned plug-in folders first.
2. Extract the ZIP. In Finder press Command–Shift–G and enter `~/Library/Audio/Plug-Ins/Components/`. Copy `Polychip Console.component` there. It uses the same instrument identity as older versions; it does not install beside them as another instrument.
3. Reopen the host and look on a **software-instrument track**, in its instrument slot under **AU Instruments → Jesse → Polychip Console**. The Library patch browser and an audio-effect insert are different selectors. Visibility in GarageBand remains unconfirmed.
4. Start quietly in a new test project or a copy. Preserve important saved projects. Check note release, sustain, Panic, automation, save/reopen, interface resizing and real-time performance before relying on it.

Review normal macOS opening/trust prompts. This guide does not ask you to remove quarantine, disable security, reset caches or re-sign the component. No installer script is included.

Read [automated-check limits](AUTOMATED-VALIDATION.md), [build identity](BUILD-INFO.json) and [complete notices](THIRD-PARTY-NOTICES.txt). Keep those files with the component. Use the public repository's Issues tab for an intentional minimal report, without private projects, recordings or full logs containing personal paths.
