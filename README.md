# Sidebar Expand on Hover
![](./screenshot.png)

Zen mod to auto expand the sidebar on hover.

- **IMPORTANT**: Turn the mod off or on with the fullscreen toggle (F11)
- **IMPORTANT**: Use the mod in single toolbar or multiple toolbars mode, never on collapsed toolbar mode

## Custimization Options
In the mods menu, clicking on the gear icon will give you several customization options:
- Make all essential tabs visible in the collapsed sidebar
- Fade unloaded (sleeping) tabs
- Control Collapsed and expanded widths
- Control the delay to expand and animation Speeds
- Hide or show the workspace indicator

---

## Compatibility
Zen 1.23b Library (including Media, Downloads, and History) uses the sidebar's
measured width to move the page aside. The mod keeps that box at the collapsed
width while laying out its toolbar contents at the configured expanded width.
This lets Library use its native spring animation throughout opening and
closing, without extra page margins or a second sidebar-retraction stage.
Library's native panel size and clipping are unchanged. Normal hover animation,
collapse delay, left/right placement, and the fullscreen toggle are preserved.
Verified in an isolated Zen 1.23b profile across all three performance modes,
single/multiple toolbars, both sidebar sides, and custom widths.

## Using this fork

The Zen Mods store entry points to the original repository. To use the fixes in
[this fork](https://github.com/alkali210/zen-sidebar-expand-on-hover), choose one
of the following methods.

### Option 1: Replace the installed mod's CSS

1. Install **Sidebar Expand on Hover** from Zen Mods if it is not already installed.
2. Open `about:profiles` and open the **Root Directory** of the profile currently in use.
3. Find the mod's folder under `chrome/zen-themes/<mod-id>/`. Use `zen-themes.json` in the profile root to identify the matching mod ID.
4. Download the raw [chrome.css](./chrome.css) from this fork. Close Zen, back up the installed mod's `chrome.css`, and replace it with the downloaded file.
5. Start Zen and toggle the mod off and on in Zen Mods to rebuild the stylesheet cache.

### Option 2: Install with Sine

1. Install [Sine](https://github.com/CosmoCreeper/Sine#installation) if you do not already use it.
2. Disable the original **Sidebar Expand on Hover** mod in Zen Mods to avoid loading both versions.
3. In Sine's custom repository installation field, enter `alkali210/zen-sidebar-expand-on-hover` and install it.
4. Enable the mod in Sine and restart Zen. Updates managed by Sine will come from this fork.
