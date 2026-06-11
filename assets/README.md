# Image assets

Real product screenshots go in this folder. The site is wired so each image
below replaces its CSS-illustrated placeholder automatically — no HTML changes
needed. Until a file exists, the illustrated mock shows instead (labelled
"illustrative mock" on the page).

## Slots

| File | Used on | What to export (screens from the old portfolio that fit) |
|---|---|---|
| `sitemate-hero.png` | sitemate.html — top of page | Dashpivot web app overview: the column workflow (Draft → In progress → Complete). ~1760px wide (2x of 880px). |
| `sitemate-signatures.png` | sitemate.html — Feature story 01 | The configurable signature field / permissions config UI. ~1760px wide. |
| `sitemate-actions.png` | sitemate.html — Feature story 02 | The **"My Actions"** view or **"Maintenance Checklist"** screenshots from the old Actions case study — or a web + mobile composite. ~1760px wide. |
| `sitemate-design-system.png` | sitemate.html — Design systems section | The type/colour spec sheet (the "Roboto / Ag / validation colours" shot) or the **Atoms → Molecules → Organisms** composite from the old design system case study. ~1760px wide. |
| `sitemate-card.png` | index.html — Sitemate case study card | A single hero screen cropped to roughly 4:3. ~720px wide (2x of 360px). |
| `ds-hero.png` | design-systems.html — top of page | The type/colour spec sheet (the "Roboto / Ag / validation colours" shot) from the old design system case study. ~1760px wide. |
| `ds-atomic.png` | design-systems.html — Approach section | The **Atoms → Molecules → Organisms** composite from the old case study. ~1760px wide. |
| `ds-storybook.png` | design-systems.html — Storybook section | The **Badge before/after** shots (or the Storybook prototype screen) from the old Storybook case study. ~1760px wide. |
| `design-system-card.png` | index.html — Design systems case study card | A component sheet crop at roughly 4:3. ~720px wide. |

## How to get them in

Screenshots pasted into chat don't reach the repository — upload the actual
files instead. Easiest path: on github.com, switch to this branch, open
`assets/`, then **Add file → Upload files** with the exact filenames above.
(Or commit them locally / drag them into a Figma export with these names.)

## Tips

- PNG or WebP both work (keep the `.png` filename, or update the `src` in the HTML).
- Flatten screenshots onto a clean background in Figma before exporting —
  the site adds its own frame, border, and shadow.
- Blur or replace any real customer data before publishing.
- Sources: your Figma files, the old portfolio (jennyyuedesign.com), or
  fresh exports from a Dashpivot demo workspace.
