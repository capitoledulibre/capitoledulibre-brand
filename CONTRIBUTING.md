# Contributing

Thanks for helping maintain the Capitole du Libre visual material.

## Where things go

- `brand/logo/` and `brand/icon/` — timeless assets (logos, icons, favicons).
  Change only when the visual identity itself evolves.
- `brand/print/`, `brand/social/`, `brand/video/` — multi-year templates
  reusable across editions (photobooth/plan kakemonos, Twitter banner
  template, explainer video, etc.). Files here may have a year tag
  to mark when they were last revised, but are not edition-specific.
- `editions/<year>/` — communication material produced for a specific
  edition: posters, social-media thumbnails, badges, signage, etc.
  Each edition folder should contain a short `README.md` with the event
  dates, the theme/slogan if any, and credits for the designer(s).
- `sources/` — editable source files (`.afdesign`, `.ai`, `.xcf`, layered
  `.psd`, etc.). Mirrors the structure above. Keep these out of
  `brand/` and `editions/` so consumers only see ready-to-use exports.

## File naming

- `kebab-case`, ASCII only, no accents or spaces.
- Keep `capitoledulibre` in the filename when the asset is meant to be
  downloaded and reused standalone — the folder context is lost once
  the file leaves the repository.
- Add a descriptive suffix: `-horizontal`, `-square`, `-monochrome`,
  `-16px`, `-512px`, etc.

## Large files

If you add binaries larger than a few megabytes (high-resolution PDFs,
layered PSDs, etc.), open an issue first — we may want to enable Git
LFS before merging.

## License

By contributing, you agree that your contribution is released under
the same terms as the rest of the repository (CC BY 4.0, see
[`LICENSE`](LICENSE)). For logo usage, please also read
[`TRADEMARK.md`](TRADEMARK.md).
