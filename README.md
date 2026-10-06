# ordl-zero-noctilucent

**Open Research and Development Laboratories** - <u>ordl-zero-noctilucent</u> | *shining at night*

>  “<u>**Noctilucent**</u>” means “*<u>shining at night</u>*.” For this theme, I meant <u>***light** emerging from **darkness***</u>: a *quiet* graphite background, a <u>luminous</u> porcelain shape, and a *<u>thin</u>* copper edge. The name describes that <u>visual</u> *<u>**idea**</u>*, <u>something bright enough to catch your eye without lighting up the whole screen</u>. The intended title is **Zero** <u>**Noctilucent**</u>;


# ORDL Zero Noctilucent

ORDL Zero Noctilucent | original palette by Maya Magikami (nlda lineage) for community from ORDL

Community review package from ORDL for Aether/Omarchy. No installation or activation was performed by the packager.

## Contents
The root preserves the shape of Baked (An aether barebones save): colors.toml, icons.theme and backgrounds. A separately named blueprint, optional standalone snippets, native-v4 palette alternative and design/evidence documents extend that barebones structure.

## Review in Aether
The official documentation supports importing a colors.toml or a blueprint JSON. Import the root colors.toml or ordl-zero-noctilucent.blueprint.json into the editor, then select backgrounds/ordl-zero-noctilucent.png from your extracted folder. No absolute wallpaper path is stored because the destination is your choice. Review with Live Apply off. Do not use an auto-apply option when merely reviewing.

## Installation boundary
Do not copy this entire folder over an existing config directory. standalone/ files are optional include/theme snippets, not whole application configuration replacements. Native Omarchy uses its own loader and generated files; see docs/CONFIGURATION-COVERAGE.md before deciding what to use. On GNOME, a palette alone does not replace GNOME Shell or GTK styling. No installer or automatic activation script is supplied.

The original Baked archive remains unchanged. Retain your existing theme and configs for rollback. Full native application compatibility remains unverified.

## Exact blueprint and wallpaper paths
The blueprint is ordl-zero-noctilucent/ordl-zero-noctilucent.blueprint.json and the wallpaper is ordl-zero-noctilucent/backgrounds/ordl-zero-noctilucent.png. From the cloned package repo, the documented import command is:

```sh
aether --import-blueprint ./ordl-zero-noctilucent.blueprint.json
```

Then select ./backgrounds/ordl-zero-noctilucent.png in Aether. The blueprint deliberately contains no machine-specific absolute wallpaper path. No new ID field has been invented.

## Checksums
From the cloned package repo, `sha256sum -c docs/SHA256SUMS` verifies every packaged file except the manifest itself. Paths are relative to this directory. The manifest is generated after all content changes. The ZIP SHA-256 is supplied separately in the delivery message; it cannot be embedded in its own archive without changing that checksum.

(This README.md will fail verification) ;)

This correction updates naming and references only, plus the requested palette attribution and validation documentation. Palette values, wallpaper pixels and application settings are preserved. Native application testing remains unperformed by the packager.


~
Winsock
