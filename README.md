# Hooray For Everything — synth downloads

Experimental Mac instruments for making music. Each is available as a standalone app and an Audio Unit instrument for a music host. Pick the sounds you want.

## Downloads

These are early releases and playable previews, shared for trying and feedback. They are **not production-stable builds**: full host and listening checks remain pending. Use each instrument's direct download; the generic Latest button is not a per-product selector.

| Instrument | Sound | Version and download | Mac requirement |
| --- | --- | --- | --- |
| **Adaptive Intonation** | Chords that gently retune as you play. | [ZIP 0.1.0](https://github.com/Hooray-For-Everything/synth-releases/releases/download/adaptive-intonation-v0.1.0/Adaptive-Intonation-0.1.0-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/adaptive-intonation-v0.1.0) | macOS 11.0+; Apple Silicon or Intel |
| **Tape Polysynth** | Warm keys and pads with worn-tape motion and color. | [ZIP 0.1.0-preview.1](https://github.com/Hooray-For-Everything/synth-releases/releases/download/tape-polysynth-v0.1.0-preview.1/Tape-Polysynth-0.1.0-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/tape-polysynth-v0.1.0-preview.1) | macOS 11.0+; Apple Silicon or Intel |
| **Drum Synth** | A synthesized electronic drum kit with playable pads and groove controls. | [ZIP 0.1.0-preview.1](https://github.com/Hooray-For-Everything/synth-releases/releases/download/drum-synth-v0.1.0-preview.1/Drum-Synth-0.1.0-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/drum-synth-v0.1.0-preview.1) | macOS 11.0+; Apple Silicon or Intel |
| **Harmonic Ecosystem** | Shimmering additive tones with interacting harmonics. | [ZIP 0.1.3-preview.1](https://github.com/Hooray-For-Everything/synth-releases/releases/download/harmonic-ecosystem-v0.1.3-preview.1/Harmonic-Ecosystem-0.1.3-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/harmonic-ecosystem-v0.1.3-preview.1) | macOS 12.0+; Apple Silicon or Intel |
| **Distant Metal** | Struck, scraped and bending metal, from close-up to far away. | [ZIP 0.1.0-preview.1](https://github.com/Hooray-For-Everything/synth-releases/releases/download/distant-metal-v0.1.0-preview.1/Distant-Metal-0.1.0-preview.1-macOS.zip) · [notes and notices](https://github.com/Hooray-For-Everything/synth-releases/releases/tag/distant-metal-v0.1.0-preview.1) | macOS 11.0+; Apple Silicon or Intel |

Download the named ZIP together with **START-HERE.md**, **THIRD-PARTY-NOTICES.txt** and **SHA256SUMS.txt** from its release. Keep the full notices with the software. The [root checksum list](SHA256SUMS.txt) identifies all five software ZIPs; [manifests](manifests/) record versions, requirements and exact hashes.

Mac only. The bundles use local **ad-hoc signatures and are not Developer ID signed or notarized**. Review normal macOS opening/trust prompts; do not disable security settings. Harmonic Ecosystem also contains an AUv3 extension, whose independent host discovery/loading remains unproven. There is no Windows, iPhone or iPad release here.

Read [installation guidance](INSTALL.md) before replacing a plug-in. Keep a backup outside scanned plug-in folders and try a new test project or a copy at a low monitoring level. Compilation, static signatures and offline checks do not establish complete GarageBand/Logic MIDI, automation, save/reopen, resizing, real-time performance or listening acceptance.

## Feedback and licensing

Use [public issues](https://github.com/Hooray-For-Everything/synth-releases/issues) for feedback, following [support guidance](SUPPORT.md). Share only information you intend to make public. Read the [licensing/notices policy](LICENSE-POLICY.md) and [full third-party notices](THIRD-PARTY-NOTICES.txt).

## About this repository

This repository contains reviewed binary downloads, reader documentation, notices, checksums and manifests. The instrument source code and development history are maintained separately. Existing software ZIP bytes are preserved; these public upload dates are not the original compile dates.

GitHub's automatic **Source code** ZIP/tarball is a documentation snapshot from this clean repository. Choose a named instrument ZIP under its release's **Assets** to obtain the app and plug-in.
