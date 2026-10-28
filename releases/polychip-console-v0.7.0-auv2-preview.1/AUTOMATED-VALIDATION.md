# Polychip Console 0.7.0 — checks and limits

This edition reuses the existing approved AUv2 executable unchanged. Packaging checks verify the archive paths/content, every component file hash, executable permission, 0.7.0 bundle/AU metadata, arm64 and x86_64 slices, macOS12 minimum and strict/deep ad-hoc signatures before and after extraction. No source/DSP change or rebuild was performed.

The identical AUv2 binary has recorded normal and out-of-process Audio Unit validation passes, including MIDI/render tests and100 parameters. Earlier exact-binary automated gates cover initialization, parameter ranges, state/MIDI/lifecycle and disposal. Prior engine sanitizer/regression records include45 historical audio hashes and seven deterministic pulse examples; those engine tests were not rerun by this documentation-only packaging task.

**GarageBand recognition is unresolved.** Earlier evidence includes a system-policy rejection; current validation passes did not establish its present menu visibility or host instantiation. No current root cause or new blocking synth defect was confirmed by that diagnosis. Full GarageBand/Logic behavior, automation, save/reopen, window interaction, CPU/audio dropouts and live listening remain pending. Out-of-process AUv2 validation is not AUv3 validation.

Only the validated AUv2 format is included. Standalone and AUv3 are omitted from this edition; no claim about an installed app or its extension is implied. Ad-hoc signing is not Developer ID signing or notarization. No install, app/host launch, cache/security change, audio-device use or saved-project edit was performed by this packaging task.
