<h1 align="center">
  🦊 MaterialFox, pssmst's fork
</h1>

<h2 align="center">
  A Firefox user CSS theme that looks similar to Chrome.
</h2>

## 🚀 Getting Started

1. **Open** Firefox and type `$${\color{#1fe250}\text{about:config}}$$` in the address bar, then press <kbd>Enter</kbd>.
2. If a warning page appears, **click** `Accept the Risk and Continue` to access the `about:config` page.
3. **Search** for the following preferences using the search bar at the top of the `about:config` page, and **ensure** the following preferences are `true`:

   - `$${\color{#1fe250}\text{toolkit.legacyUserProfileCustomizations.stylesheets}}$$`
   - `$${\color{#1fe250}\text{svg.context-properties.content.enabled}}$$`
   - `$${\color{#1fe250}\text{userChrome.ui-chrome-refresh}}$$`
   - `$${\color{#1fe250}\text{userChrome.theme-chrome-refresh}}$$`
   - `$${\color{#1fe250}\text{userChrome.ui-system-font}}$$` (*Windows only*)
   
4. **Set** the following preferences to these specific values:

   - `$${\color{#1fe250}\text{full-screen-api.transition-duration.enter}}$$`: `0 0`
   - `$${\color{#1fe250}\text{full-screen-api.transition-duration.leave}}$$`: `0 0`
   - `$${\color{#1fe250}\text{full-screen-api.transition.timeout}}$$`: `0`
   - `$${\color{#1fe250}\text{full-screen-api.warning.timeout}}$$`: `1000`
   - `$${\color{#1fe250}\text{media.autoplay.default}}$$`: `0`

5. **Type** `$${\color{#ff65fc}\text{about:support}}$$` in the address bar and press <kbd>Enter</kbd>.
6. **Scroll down** to the `Profile Folder` section and **click** `Open Folder`.
7. **Download** the `chrome` file from this repository and place the folder into your Firefox profile directory.
8. **Restart** Firefox to apply the changes.

## Credits

- [material-fox-updated](https://github.com/edelvarden/material-fox-updated) by [edelvarden](https://github.com/edelvarden)
- [material-fox](https://github.com/muckSponge/MaterialFox) by [muckSponge](https://github.com/muckSponge)
- [edge-frfox](https://github.com/bmFtZQ/edge-frfox) by [bmFtZQ](https://github.com/bmFtZQ)
