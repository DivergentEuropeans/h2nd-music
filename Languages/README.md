# H2ND downloadable languages

These are small text-only language packs, not translation models. Spanish is a
partial sample, not a complete translation. English remains built into the app.

The app's list address is:

https://raw.githubusercontent.com/DivergentEuropeans/h2nd-music/main/Languages/catalog.json

Nothing becomes available online until these files are committed and pushed to the
public hosting repository. GitHub Pages is not required for raw GitHub addresses.

In the app: Settings > Language / Idioma > Check available languages, then tap a
language to download. Once installed, it works offline. Before publication the list
will fail to load; the built-in Spanish sample and existing installed packs work.

When updating a pack, regenerate catalog.json with the preparation tool in the game
repository. Commit the language JSON and catalog together. Editing JSON directly
without updating its SHA-256 checksum makes the app reject that download.

All generated entries default to partial=true. Set partial=false only after a pack
is complete and reviewed. Preparation resets updated entries to partial=true.

To add a language, prepare its translated pack in the game repository first; do not
copy untranslated English entries and label them as a complete language.
