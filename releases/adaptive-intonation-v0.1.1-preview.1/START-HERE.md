# Adaptive Intonation 0.1.1 — Preview 1

Instrument/app/plug-in version: **0.1.1**. Download edition: **Preview 1**. Mac only; macOS 11.0 or later, Apple Silicon or Intel. Contains a universal AUv2 instrument and standalone app; no AUv3/iOS/Windows build.

## What changed

- A smaller display-aware window, responsive down to 900×620, keeps the keyboard visible.
- Smaller dials and finer vertical Shape dragging; exact numeric entry remains available.
- Stable held-note target-tuning information, numeric black-key offsets and readouts for all distinct held notes.
- Existing parameter IDs, factory-program order, saved-state format and tuning/DSP behavior are preserved.

## Trying it

Keep this guide, the complete `THIRD-PARTY-NOTICES.txt` and release checksums with the software. Verify the downloaded ZIP against the release's `SHA256SUMS.txt`.

For standalone use, extract and copy the app to Applications, keeping a backup of an older app. For the AUv2, quit your music host before changing plugins. Back up the previous component **outside scanned plugin folders**, then copy `Adaptive Intonation.component` into `~/Library/Audio/Plug-Ins/Components/`. Reopen the host and look under **AU Instruments → Jesse**. Use a new test project or a copy at a low monitoring level; preserve important projects and previous software until you have checked recall.

These bundles are **ad-hoc signed, not Developer ID signed or notarized**. Review normal macOS opening/trust prompts; do not disable security settings. An unsuccessful opening/scan needs diagnosis rather than automatic cache/service resets.

## Preview limits and checks to try

Automated builds, static metadata/signature checks and offline tests do not establish complete real-host or musical acceptance. Logic/GarageBand confirmation remains pending. Please try:

1. Confirm the editor reports **0.1.1**, fits your display/host zoom, resizes down, and shows the keyboard fully.
2. Play white-key and black-key chords from MIDI; check that every held note has a target-cents readout. Scroll the keyboard for notes outside its initial range.
3. Try fine Shape movements near its top and exact value entry; judge its musical behavior.
4. Check presets, automation and saving/reopening a new test project or copy before relying on the build in existing work.

Values shown are solved **target cents**, separate from smoothed sounding pitch and detune. Report the instrument version, ZIP checksum, macOS/host versions and reproducible steps through the public support links, sharing only information you intend to make public.

Public downloads and support: https://github.com/Hooray-For-Everything/synth-releases
