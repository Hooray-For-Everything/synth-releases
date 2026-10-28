# Trying a Mac instrument

1. Choose a named instrument ZIP from its product-specific release. Also keep START-HERE.md, THIRD-PARTY-NOTICES.txt and SHA256SUMS.txt with it.
2. Check the stated minimum macOS version. All current downloads include Apple Silicon and Intel binaries. The minimum is a build requirement, not proof of compatibility on every OS version.
3. Extract the ZIP. For standalone use, copy the app to Applications, keeping a backup if you replace an older app.
4. For an AUv2 music-host plug-in, quit the host. In Finder press Command–Shift–G and enter `~/Library/Audio/Plug-Ins/Components/`. Back up any older component outside scanned plug-in folders, then copy the new `.component` there. Reopen your host and look under **AU Instruments → Jesse**.
5. Start quietly in a new test project or a copy. Keep important saved projects intact until you have checked MIDI, automation, save/reopen and the interface.

These bundles are ad-hoc signed and **not Developer ID signed or notarized**. Review normal macOS opening/trust prompts. This guide does not ask you to disable system security or remove quarantine information. An AUv2 result is not evidence that an embedded AUv3 extension loads independently.

To compare downloaded bytes with the release manifest, run `shasum -a 256 -c SHA256SUMS.txt` in the folder containing that release's named files. Matching hashes identify the published bytes; they do not replace Apple's trust checks or establish host compatibility.
