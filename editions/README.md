# Editions

This directory holds communication material produced for each
edition of Capitole du Libre (posters, social-media thumbnails,
badges, signage, etc.).

## Convention

One folder per year, grouped by intended use:

```
editions/
└── <year>/
    ├── README.md       # dates, theme/slogan, designers, languages
    ├── poster/         # main posters (multiple formats and languages)
    ├── social/         # social-media banners, Open Graph images, post visuals
    ├── print/          # programs, flyers, badges, stickers
    └── signage/        # on-site signage: kakemonos, totems, panels
```

Empty subfolders contain a `.gitkeep` placeholder. Remove it once
real assets are added, or delete the subfolder if a given edition
does not need it.

Editable source files (`.afdesign`, `.ai`, `.xcf`, ...) belong in
`sources/<year>/`, not here.

Event photos can get very large; consider a separate repository
(e.g. `capitoledulibre-photos` with Git LFS) or external storage,
and link to it from the edition's `README.md`.
