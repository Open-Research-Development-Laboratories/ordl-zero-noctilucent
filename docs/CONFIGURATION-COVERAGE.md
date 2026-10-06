# Configuration inventory and limits

## Included
- All original Baked colors.toml keys, with 16 ANSI slots and semantic/extended roles.
- Aether blueprint JSON: named palette, dark mode, extended UI colors, four locked anchor slots and all twelve neutral adjustment values. No machine-specific wallpaper path is invented; select the included PNG after extraction.
- Existing Yaru-purple icon-theme identifier retained as a compatibility choice. Icon artwork is not bundled, and installation availability is unverified.
- Alternative native Omarchy v4 semantic colors.toml, kept separate from the Baked-compatible root file.
- Standalone optional color/config files for Kitty, Ghostty, Alacritty, Foot, Chromium, Hyprland, Hyprlock, Mako, Waybar, Walker, Wofi, SwayOSD, btop, VS Code color theme data and Zed theme data.
- Original wallpaper in backgrounds/.

## Documented features inventoried, not all activated
Aether supports extraction modes, 12 adjustment controls, light/dark themes, anchor locks, per-app color overrides, icon selection, blueprint import/export, wallpaper filters and blur, custom templates and standalone app destinations. It also has remote-control IPC, reload hooks and post-apply scripts. These are capabilities, not a requirement to enable every setting at once. This package uses a deliberate final palette, neutral adjustments and no destructive/post-apply hooks. No online wallpaper fetching or remote-control listener is configured.

## Version-dependent or intentionally omitted
The current Aether docs distinguish standalone output from native Omarchy generation. Native Omarchy may generate its own application files and ignore standalone overrides. Current upstream also filters executable Lua and some terminal/extension files for repository-installed themes. Therefore standalone/ is kept separate for explicit review rather than presented as universally active. The inspected Neovim template requests external plugins; it is not included. Vencord changes a third-party client and is not included. Warp and Zellij were inventoried but no validated custom configs were produced. GTK app overrides are removed by the inspected blueprint parser, so no full GNOME/GTK skin is claimed. No compositor installation, keybindings, monitor settings, auto-start, security settings or extension downloads are included.

## Validation scope
TOML/JSON parsing, original key coverage, palette hex ranges, blueprint shape, resolved values, archive integrity and selected contrast ratios are tested locally. No native Aether, Omarchy, Waybar, Hyprland, GNOME, editor or terminal application test has been run. Compatibility must be checked against the installed versions before applying. This is a reviewable package, not a claim of universal desktop validation.
