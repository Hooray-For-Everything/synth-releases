# Hooray For Everything — synth downloads

Experimental Mac instruments for making music. Most downloads include a standalone app and an Audio Unit instrument for a music host; the Polychip edition below is AUv2-only. Pick the sounds you want.

## Downloads

These are early releases and playable previews, shared for trying and feedback. They are **not production-stable builds**: full host and listening checks remain pending. Use each instrument's direct download; the generic Latest button is not a per-product selector.

| Instrument | Sound | Instrument version | Download edition | Mac requirement |
| --- | --- | --- | --- | --- |
| **Adaptive Intonation** | Chords that gently retune as you play. | **0.1.1** | Preview 1 · [ZIP](https://github.com/Hooray-For-Everything/synth-releases/releases/download/adaptive-intonation-v0.1.1-preview.1/Adaptive-Intonation-0.1.1-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/adaptive-intonation-v0.1.1-preview.1) | macOS 11.0+; Apple Silicon or Intel |
| **Tape Polysynth** | Warm keys and pads with worn-tape motion and color. | **0.1.0** | Preview 1 · [ZIP](https://github.com/Hooray-For-Everything/synth-releases/releases/download/tape-polysynth-v0.1.0-preview.1/Tape-Polysynth-0.1.0-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/tape-polysynth-v0.1.0-preview.1) | macOS 11.0+; Apple Silicon or Intel |
| **Drum Synth** | A synthesized electronic drum kit with playable pads and groove controls. | **0.1.0** | Preview 1 · [ZIP](https://github.com/Hooray-For-Everything/synth-releases/releases/download/drum-synth-v0.1.0-preview.1/Drum-Synth-0.1.0-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/drum-synth-v0.1.0-preview.1) | macOS 11.0+; Apple Silicon or Intel |
| **Harmonic Ecosystem** | Shimmering additive tones with interacting harmonics. | **0.1.3** | Preview 1 · [ZIP](https://github.com/Hooray-For-Everything/synth-releases/releases/download/harmonic-ecosystem-v0.1.3-preview.1/Harmonic-Ecosystem-0.1.3-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/harmonic-ecosystem-v0.1.3-preview.1) | macOS 12.0+; Apple Silicon or Intel |
| **Distant Metal** | Struck, scraped and bending metal, from close-up to far away. | **0.1.0** | Preview 1 · [ZIP](https://github.com/Hooray-For-Everything/synth-releases/releases/download/distant-metal-v0.1.0-preview.1/Distant-Metal-0.1.0-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/distant-metal-v0.1.0-preview.1) | macOS 11.0+; Apple Silicon or Intel |
| **Polychip Console** | NES, Game Boy and FM-style chip sounds with shared echo, modulation and tone. | **0.7.0** | AUv2 preview 1 · [ZIP](https://github.com/Hooray-For-Everything/synth-releases/releases/download/polychip-console-v0.7.0-auv2-preview.1/Polychip-Console-0.7.0-AUv2-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/polychip-console-v0.7.0-auv2-preview.1) | macOS 12.0+; Apple Silicon or Intel |

**Polychip preview caveat:** GarageBand recognition remains unresolved despite passing normal and out-of-process AUv2 validation. This **AUv2-only** download refreshes packaging/documentation for unchanged instrument version **0.7.0**; it contains no standalone app or AUv3. Full host/listening acceptance remains pending. Read its [versioned guide](releases/polychip-console-v0.7.0-auv2-preview.1/START-HERE.md) and [complete notices](releases/polychip-console-v0.7.0-auv2-preview.1/THIRD-PARTY-NOTICES.txt) before trying it.

**Version labels:** “Instrument version” is the numeric version reported by the app/plug-in. “Preview 1” is the download's prerelease edition. For example, a ZIP named `Tape-Polysynth-0.1.0-preview.1-macOS.zip` contains instrument version **0.1.0**. Existing filenames, tags and hashes are retained; the preview suffix is not part of the numeric version stored in these app/plug-in bundles.

Download the named ZIP together with **START-HERE.md**, **THIRD-PARTY-NOTICES.txt** and **SHA256SUMS.txt** from its release. Keep the full notices with the software. The [root checksum list](SHA256SUMS.txt) identifies current and historical software ZIPs; [manifests](manifests/) record versions, requirements and exact hashes.

Mac only. The bundles use local **ad-hoc signatures and are not Developer ID signed or notarized**. Review normal macOS opening/trust prompts; do not disable security settings. Harmonic Ecosystem also contains an AUv3 extension, whose independent host discovery/loading remains unproven. There is no Windows, iPhone or iPad release here.

Read [installation guidance](INSTALL.md) before replacing a plug-in. Keep a backup outside scanned plug-in folders and try a new test project or a copy at a low monitoring level. Compilation, static signatures and offline checks do not establish complete GarageBand/Logic MIDI, automation, save/reopen, resizing, real-time performance or listening acceptance.

Adaptive Intonation **0.1.1 Preview 1** adds a compact editor, finer Shape dragging and complete target-tuning readouts. Its numeric instrument/bundle version is **0.1.1**; the preview suffix identifies the download edition. [Versioned guide](releases/adaptive-intonation-v0.1.1-preview.1/START-HERE.md) and [complete notices](releases/adaptive-intonation-v0.1.1-preview.1/THIRD-PARTY-NOTICES.txt) accompany this build. The [historical 0.1.0 release](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/adaptive-intonation-v0.1.0) remains unchanged.

## Feedback and licensing

Use [public issues](https://github.com/Hooray-For-Everything/synth-releases/issues) for feedback, following [support guidance](SUPPORT.md). Share only information you intend to make public. Read the [licensing/notices policy](LICENSE-POLICY.md) and [full third-party notices](THIRD-PARTY-NOTICES.txt).

## About this repository

This repository contains reviewed binary downloads, reader documentation, notices, checksums and manifests. The instrument source code and development history are maintained separately. Existing software ZIP bytes are preserved; these public upload dates are not the original compile dates. These are fixed early-release/preview snapshots. A version number alone does not distinguish every development build; use the ZIP checksum to identify the exact public download.

GitHub's automatic **Source code** ZIP/tarball is a documentation snapshot from this clean repository. Choose a named instrument ZIP under its release's **Assets** to obtain the app and plug-in.
