# Malayalam Wikisource Catalog

Catalogue of 580 books digitised and proofread by the Malayalam Wikisource community, with metadata drawn from Wikidata.

**File:** `mlwikisource_-_ml-wikisource-catalog.csv` (UTF-8, comma-separated, 580 rows, one per Wikidata item)

## Columns
| Column | Wikidata property | Notes |
|---|---|---|
| item | – | Wikidata Qid (unique key) |
| titles | P1476 | Title |
| authors | P50 | Labels; empty for ~35% of rows |
| editors | P98 | Sparse |
| translators | P655 | Sparse |
| languages | P407 | Mostly Malayalam; some Arabi Malayalam, English, Sanskrit |
| numberOfPages | P1104 | |
| commonsFiles | P996 | Scan on Wikimedia Commons (URL) |
| wikisourceIndexPages | P1957 | ml.wikisource Index page URL |
| publicationYear | P577 | Year, 1607–2016 where present |
| wikisourceSitelinks | – | ml.wikisource page; present for ~40% of rows |

Multiple values in one cell are joined with ` | `. Empty cells mean the property is not recorded on Wikidata.

## Provenance
Extracted from the Wikidata Query Service using a SPARQL query over a list of 580 Qids drawn from the Malayalam Wikisource book list. Retrieved: 2026-10-26.

## Licence
Wikidata structured data is released under CC0 1.0, and this dataset is likewise released under **CC0 1.0 Universal**. The books themselves are not included, only metadata and links.

## Citation
Karingamadathil, M., & Parampatt, J. (2026). Malayalam Wikisource Catalog [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.23649122.
