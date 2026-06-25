# Translation Notes

- Source format: selectable-text PDF.
- Workflow: `nature-reader` style paragraph-level bilingual reader.
- Body text is preserved as source-anchored `Original` / `中文` pairs.
- Figure handling repaired on 2026-06-11: the main figures are now cropped individually as `assets/fig-01.png` through `assets/fig-08.png`; full-page visual-reference screenshots are no longer used in `paper.md` or `source_map.json`.
- References are retained in the PDF and not translated as body paragraphs.
- Machine translation was used as a draft translation aid; terminology, front matter, guide text, figure notes, and related-reading decisions were curated for the user's reading workflow.

## 2026-06-25 Quality Audit

- Rechecked against the `nature-reader` contract: paragraph-level bilingual pairs, figure cards, `source_map.json`, and image links all pass structural validation.
- Removed publisher caption text from Fig. 1, Fig. 6, and Fig. 7 image crops while preserving panel labels, axes, legends, and plotted data.
