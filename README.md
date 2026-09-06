<h1 align="center">
  🦊 MaterialFox, pssmst's fork
</h1>

<h2 align="center">
  A Firefox user CSS theme that looks similar to Chrome.
</h2>

## 🚀 Getting Started

1. **Open** Firefox and type `about:config` in the address bar, then press <kbd>Enter</kbd>.
2. If a warning page appears, **click** `Accept the Risk and Continue` to access the `about:config` page.
3. **Search** for the following preferences using the search bar at the top of the `about:config` page, and **ensure** the following preferences are `true`:

   - `toolkit.legacyUserProfileCustomizations.stylesheets`
   - `svg.context-properties.content.enabled`
   - `userChrome.ui-chrome-refresh`
   - `userChrome.theme-chrome-refresh`
   - `userChrome.ui-system-font` (*Windows only*)
   
4. **Set** the following preferences to these specific values:

   - `full-screen-api.transition-duration.enter`: `0 0`
   - `full-screen-api.transition-duration.leave`: `0 0`
   - `full-screen-api.transition.timeout`: `0`
   - `full-screen-api.warning.timeout`: `1000`
   - `media.autoplay.default`: `0`

5. **Type** `about:support` in the address bar and press <kbd>Enter</kbd>.
6. **Scroll down** to the `Profile Folder` section and **click** `Open Folder`.
7. **Download** the `chrome` file from this repository and place the folder into your Firefox profile directory.
8. **Restart** Firefox to apply the changes.

## Credits

- [material-fox-updated](https://github.com/edelvarden/material-fox-updated) by [edelvarden](https://github.com/edelvarden)
- [material-fox](https://github.com/muckSponge/MaterialFox) by [muckSponge](https://github.com/muckSponge)
- [edge-frfox](https://github.com/bmFtZQ/edge-frfox) by [bmFtZQ](https://github.com/bmFtZQ)
