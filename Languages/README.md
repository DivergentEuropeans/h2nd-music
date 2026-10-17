# H2ND downloadable languages

`es.json` is the expanded Spanish pack (about 190 KB). It covers menus, actions,
story messages, tutorials, stock reports, drawing and minigame UI. English remains
built into the app. Downloaded languages work offline.

The Spanish pack is still marked `partial: true`: wording and phone layouts need
review. Typing/spelling game answers stay English so the displayed word matches
the game's input checks. Proper names and stock tickers also remain unchanged.

The app checks:

https://raw.githubusercontent.com/DivergentEuropeans/h2nd-music/main/Languages/catalog.json

To make a local update available, commit and push **both es.json and catalog.json**
to the public repository. Preparing these files does not publish them. GitHub Pages
is not required for this raw-file address.

Players need the updated app for translated joined stories, image headings,
drawing and minigames. Then choose Settings > Language / Idioma > Check available
languages > Download latest: Español. Existing language files are not replaced
silently.

When changing a translation, use the game repository's preparation tool to update
catalog.json with the correct checksum. Do not edit the hosted file alone: a
mismatched checksum makes the app reject the download. The editable source and
validation instructions are in the game repository's translations folder.

The language system has no translation SDK or language models. The large Spanish
pack is downloaded only when requested and is not bundled into the English APK.
