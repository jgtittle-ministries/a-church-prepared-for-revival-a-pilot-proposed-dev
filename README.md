# A Church in Revival — A Pilot Proposed (DEV)

**This is the working DEV repository.** Content here is draft, under active revision, and not yet authoritative. The published edition will live at [`a-church-in-revival-a-pilot-proposed`](https://github.com/jgtittle-ministries/a-church-in-revival-a-pilot-proposed) once mirrored.

**Read the book:** https://jgtittle-ministries.github.io/a-church-in-revival-a-pilot-proposed-dev/

A proposal offered to a church asking two questions: *Do you want a revival? And if yes, what might it take to prepare the soil?* Four movements — the question, the soil, the preparation, the keeping — with a Reference section pointing into [*Intentional Journey of the Heart*](https://jgtittle-ministries.github.io/Intentional-Journey-of-the-Heart/) as the foundation base and [*Fellowship of the Heart*](https://jgtittle-ministries.github.io/fellowship-of-the-heart-pilot-at-cca/) as the leadership-formation pilot it leans on.

## Repo mechanics

- Static markdown reader (same engine as the sibling books): `index.html` redirects into `reader.html`, which renders `docs/**/*.md` per `manifest.js`.
- `manifest.js` and `search-index.js` are **generated** — do not hand-edit:
  - `node tools/build-manifest.mjs`
  - `node tools/build-search-index.mjs`
- Workflow: all changes land here (dev) first; mirrored to the prod repo only on the author's explicit word.

## License

Text and materials © John G. Tittle, licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
