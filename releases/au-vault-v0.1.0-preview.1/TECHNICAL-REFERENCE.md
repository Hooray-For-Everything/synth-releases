# AU Vault 0.1.0 — Preview 1

A local hub for preserving exact Audio Unit builds, keeping manual project profiles and browsing Hooray For Everything's public instrument releases.

**This preview does not switch installed plugins. Live activation and restoration are disabled.** A separate development workflow exists, but real GarageBand/Logic musical recall has not been accepted. Downloading, importing, pinning and dry runs never replace an installed plugin.

## Requirements and opening

- Apple Silicon Mac (arm64), macOS 14 or later. This download does not support Intel Macs.
- Internet access for public release browsing/downloads; local inventory, archives and profiles work offline.
- Unzip the download into a local folder and open AU Vault.app. No installer, administrator access, account or credentials are required.
- The app is **ad-hoc signed, not Developer ID signed or notarized**. macOS may block it. Review normal macOS trust prompts only if you choose to trust the preview; do not disable Gatekeeper, remove quarantine or change security permissions to bypass a block. Report the exact message if your Mac will not open it.

Keep this guide, BUILD-INFO.json and THIRD-PARTY-NOTICES.txt with the app. SHA256SUMS.txt and MANIFEST.json on the release identify this exact download. There is no background agent, telemetry, unattended update or login service.

## A short tour

1. **Bundle / Scan report:** inspect installed declarative AUv2 components, versions, architectures, signatures and exact bundle fingerprints. Inspection does not execute a plugin. Some older resource-only plugins are shown as unsupported.
2. **Archive & Projects:** archive complete self-contained bundles outside the scanned folders. The default is `~/Library/Application Support/AUVault/Archive`. Use local storage outside iCloud/File Provider Documents; metadata-changing destinations fail preservation checks. Existing files are not silently overwritten.
3. **Archived instruments:** expand an instrument to see its exact builds. Same names with different AU identities stay separate. **Pin build** selects that exact build for the current profile draft; it does not install, activate, favorite or globally lock it. Save a new profile JSON to retain choices; Open profile restores them. Profiles are manual, separate from GarageBand projects.
4. **Create dry-run plan:** read hypothetical changes and blockers. No Apply operation is enabled in this public preview. One future active build per AU identity would be shared across the Mac, not isolated per simultaneous project.
5. **Public releases:** choose Read all public releases, then an instrument version/download edition. **Download & inspect** verifies the published checksum and actual AU identity/version/static signature. Review it, then choose **Import into local archive**. This keeps the exact ZIP/notices and AUv2 bundle without running or installing its standalone app/AUv3. Switch to Archive & Projects to pin it manually.

## Versions and update information

Instrument version, download edition/tag and exact build fingerprints are separate. For example, an instrument version 0.1.0 can be distributed as Preview 1, with a ZIP filename containing 0.1.0-preview.1. Two builds with the same numeric version can still differ. “Available” or “newer” is not permission to replace a pinned build; no unattended replacement happens here.

The hub lists actual compatible releases hosted in Hooray-For-Everything/synth-releases, including prereleases and older hosted editions. It does not invent missing historical builds, compile source commits or import GitHub's source-code documentation ZIP as a plugin. The current reviewed instrument families are Adaptive Intonation, Tape Polysynth, Drum Synth, Harmonic Ecosystem Distant Metal and Polychip Console; other formats/families need review.

## Preview limits and recovery

- Grouping/profile, activation failure paths and public-import safeguards pass deterministic tests; all seven currently hosted public instrument ZIPs were statically downloaded/imported in an isolated durable validation archive. No downloaded plugin was executed in that verification.
- The running Release catalog, grouped profile save/reopen, dry-run and isolated import UI have been inspected and photographed; full visual acceptance remains pending. Real host loading, parameter/automation recall, audio and musical approval remain untested for the full workflow. The app does not scan project dependencies or edit saved music.
- Public live activation/restoration controls and backend entry points are disabled. Do not treat a dry-run description as a completed switch.
- Archives preserve complete contents/modes/internal symlinks/xattrs. Owner editing is detected rather than prevented; ACLs are copied but not included in the current tree digest. Power-loss/fsync guarantees are not claimed.
- Import limits are 256 MiB compressed, 1 GiB expanded and 20,000 entries. Unsafe paths, case aliases, links, encrypted/special entries and unsupported package layouts fail closed. Failed/cancelled evidence is retained in the local Downloads area; there is no import receipt or activation for a failed transfer.
- Never delete an interrupted stage/journal just to bypass a blocker. Keep the original and evidence. The supported manual recovery is verified reimport into a separate clean local archive; ask for help if unsure.

This is experimental software. Preserve your own backups. Send public feedback at https://github.com/Hooray-For-Everything/synth-releases/issues and include the AU Vault version and the relevant message; do not attach private music, profiles or credentials unless you intentionally choose to share them.
