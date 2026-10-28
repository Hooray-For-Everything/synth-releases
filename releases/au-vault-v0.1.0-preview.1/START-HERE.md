# AU Vault — a quick guide

Keep the instrument versions your songs need, and find new releases in one place.

**Preview 1 adds downloads to your library. It does not install updates or switch the instruments used by your music apps yet.** Your songs and installed instruments stay as they are.

## Open AU Vault

You need an Apple Silicon Mac running macOS 14 or later. Unzip the download, keep the included guide and notices, and open **AU Vault.app**. No account or installer is needed. This early preview is ad-hoc signed, not Developer ID signed or notarized; macOS may block it. Do not disable security settings to get around a block.

For illustrated steps, see [the picture tour](SCREENSHOT-TOUR.md).

## Find an update or an older version

1. Open **Public releases** and choose **Read all public releases**.
2. Find your instrument. Newer and older hosted releases appear together, including previews. Check the instrument version and download edition.
3. Choose **Download & inspect** beside the edition you want. AU Vault checks that it received the published download and the expected instrument.
4. Review the result, then choose **Import into local archive** to add it to your library.

Importing makes that exact build available for a song profile. It does **not** install it into GarageBand or change any existing profile. You can browse and download without a GitHub account. Only versions actually published in the supported public repository are available; missing historical versions cannot be reconstructed here.

## Make a profile for a song

A profile is a saved list of the exact instrument builds you chose for a song. You select them yourself; AU Vault does not read or change your GarageBand song file.

1. Open **Archive & Projects**. This is your library of preserved instrument builds. You can also select an installed instrument in **Bundle** and choose **Archive complete bundle** to preserve it first.
2. Expand an instrument to see its archived builds. Choose **Pin build** beside the one your song needs. Pin means “use this build in this profile”; it is not a favorite or an installation command.
3. Give the profile your song's name. Add other instrument builds the same way.
4. Choose **Save new profile…** and save it alongside your song, or in another folder you choose. Choose a new filename; AU Vault does not overwrite an existing profile.
5. Use **Open profile…** to return to those choices later.

Different builds can share a version number, so AU Vault keeps them separate. Selecting another build of the same instrument replaces that instrument's choice in the current profile draft. Save a new profile to keep the changed choices.

## See what a song would need

Open its profile and choose **Create dry-run plan**. Read which archived builds differ from your installed instruments and any issues that need attention. A dry run is a preview only: this public release cannot apply the changes.

When switching is ready in a later release, one active build of an instrument will be shared across the Mac. Profiles will not let two songs use different builds of the same instrument at the same time.

## Keep your library safe

Use the default local archive, or another local folder outside iCloud/File Provider storage. AU Vault preserves complete bundles and checks the copy. Keep your own backups. If an import fails, keep the original files and the reported evidence; do not delete a journal just to dismiss the message.

For platform details, checksums, provenance, validation and preview limits, see **TECHNICAL-REFERENCE.md**, **BUILD-INFO.json**, **MANIFEST.json** and **THIRD-PARTY-NOTICES.txt**. Full GarageBand/Logic musical recall remains unverified; live switching is disabled.

Feedback: https://github.com/Hooray-For-Everything/synth-releases/issues. Include the AU Vault version and message, and leave private songs, profiles and account details out of public reports.
