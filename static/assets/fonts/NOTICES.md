# Bundled UI fonts

Served from this folder; no font is fetched from a CDN at runtime. Every font here
is licensed under the SIL Open Font License 1.1 (full text: `OFL-1.1.txt`). None
declares a Reserved Font Name.

File names carry the upstream version because `/assets/fonts/` is not
fingerprinted by the build: a new version must get a new file name, or browsers
may keep the old file cached.

## Geist-1.7.2-Variable.woff2, Geist-1.7.2-Italic-Variable.woff2, GeistMono-1.7.2-Variable.woff2

UI and monospace font. Unmodified, from the npm package `geist@1.7.2` (font version 1.800).

Copyright (c) 2023 Vercel, in collaboration with basement.studio
Copyright 2024 The Geist Project Authors (https://github.com/vercel/geist-font)

## Inter-3.19-Gap.woff2, Inter-3.19-Gap-Oblique.woff2

Modified version of Inter 3.019: only the characters Geist lacks (Greek, the narrow
no-break space used by French number formatting, thin / figure spaces, some currency
signs, extended Latin, Cyrillic extensions, symbols), with the `slnt` axis pinned to
0 (upright) and -10 (oblique). Built with fontTools from the Inter-Variable.ttf
previously shipped here. `app.css` maps them into the Geist family with
`unicode-range`, so they are downloaded only when such a character is on screen.

Copyright 2020 The Inter Project Authors (https://github.com/rsms/inter)

## InstrumentSerif-Regular.ttf, InstrumentSerif-Italic.ttf

Copyright 2022 The Instrument Serif Project Authors (https://github.com/Instrument/instrument-serif)

## Vazirmatn-Variable.ttf

Arabic-script font.

Copyright 2015 The Vazirmatn Project Authors (https://github.com/rastikerdar/vazirmatn)
