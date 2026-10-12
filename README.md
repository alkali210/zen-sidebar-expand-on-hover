# Sidebar Expand on Hover
![](./screenshot.png)

Zen mod to auto expand the sidebar on hover.

- **IMPORTANT**: Turn the mod off or on with the fullscreen toggle (F11)
- **IMPORTANT**: Use the mod in single toolbar or multiple toolbars mode, never on collapsed toolbar mode

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

## Custimization Options
In the mods menu, clicking on the gear icon will give you several customization options:
- Make all essential tabs visible in the collapsed sidebar
- Fade unloaded (sleeping) tabs
- Control Collapsed and expanded widths
- Control the delay to expand and animation Speeds
- Hide or show the workspace indicator
