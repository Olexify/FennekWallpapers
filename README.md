# Fennek OS wallpapers

The extra wallpapers and theme backgrounds for [Fennek OS](https://github.com/Olexify/FennekOS). They are not part of
the system itself: Fennek OS downloads a picture only when someone picks it in Settings > Personalize, and checks it
against the SHA-256 in `manifest.json` it was built with. `previews/` holds small versions Personalize shows first.

- **Amber, Sakura, Royal, Arcade, Fennek Classic, Leonote Night / Graph / Paper:** rendered from their vector sources in
  the FennekOS repo (`system_files/usr/share/fennek/*.svg`) by the `render` workflow. CC BY-SA 4.0, Fennek OS.
- **Kitsumi Night:** © Olexify.

To update after a source changes: Actions > render > Run workflow.
