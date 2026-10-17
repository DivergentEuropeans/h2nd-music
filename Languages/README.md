# H2ND downloadable languages

`es.json` is the expanded Spanish pack (about 190 KB). It covers menus, actions,
story messages, tutorials, stock reports, drawing and minigame UI. English remains
built into the app. Downloaded languages work offline.

The Spanish pack is listed as Español, without a partial label. Wording and phone
layouts can still benefit from review. Typing/spelling game answers stay English
so displayed words match the input checks. Proper names, stock tickers and original
image artwork (including English image headings) also remain unchanged.

The app checks:

https://raw.githubusercontent.com/DivergentEuropeans/h2nd-music/main/Languages/catalog.json

To make a local update available, commit and push **both es.json and catalog.json**
to the public repository. Preparing these files does not publish them. GitHub Pages
is not required for this raw-file address.

Players need the updated app for translated joined stories, drawing and minigames.
Then open Settings > Language / Idioma. The available-language list refreshes
automatically. Choose Download latest: Español to update the installed translation.
Existing language files are not replaced silently. Installed languages remain
selectable while the list loads; each has a Remove button. Built-in English does not.

When changing a translation, use the game repository's preparation tool to update
catalog.json with the correct checksum. Do not edit the hosted file alone: a
mismatched checksum makes the app reject the download. The editable source and
validation instructions are in the game repository's translations folder.

The language system has no translation SDK or language models. The large Spanish
pack is downloaded only when requested and is not bundled into the English APK.
