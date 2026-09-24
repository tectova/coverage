# Tectova coverage

Aggregate counts from Tectova's published Big Four runway record, as of 2026-09-24 (release `20260924T070753Z-97c84e5d64df`). The live pages on tectova.com are canonical; every figure here is the one those pages display for the same release, and `snapshot.json` names the data bundle and build commit it came from.

## Files

- `coverage.csv` — one row per collection year in the [archive coverage table](https://tectova.com/shows#archive-coverage), 2002 through 2026.
- `publication_accounting.json` — every candidate runway record is either published or omitted for one recorded reason, as shown in [publication accounting](https://tectova.com/methodology#publication-accounting).
- `snapshot.json` — the as-of date, release, data bundle, build commit and source hashes behind every figure.

## Columns of `coverage.csv`

| Column | Meaning |
| --- | --- |
| `collection_year` | The collection year, not necessarily the calendar year of the event ([seasons and dates](https://tectova.com/methodology#seasons-and-dates)). |
| `published_shows` | Shows on record: published canonical runway shows in the Big Four ([canonical show records](https://tectova.com/methodology#canonical-show-records), [the Big Four](https://tectova.com/methodology#the-big-four)). |
| `documented_shows` | Documented shows: the subset of those shows with a model cast on record. |
| `cite_path` | The tectova.com section that displays the row. |

These counts describe documented source-backed records, not complete industry or career totals. Coverage varies by year; a smaller count does not mean fewer shows took place.

## Archive range and published total

The CSV covers 2002 through 2026, the as-of year. Its published total is 17,809. Every published show whose collection year is after the as-of year is excluded from the current archive range; there are 265 such shows, so 17,809 + 265 = 18,074, the full published total in `publication_accounting.json`. The same figures are in `snapshot.json` under `coverage_csv`.

## Licence

The aggregate coverage figures and text in this repository (`coverage.csv`, `publication_accounting.json`, `snapshot.json`, `README.md` and `CITATION.cff`) are published by Tectova under the [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). The licence text is in [LICENSE](https://github.com/tectova/coverage/blob/main/LICENSE), the unmodified CC BY 4.0 legal code; this notice is at [NOTICE](https://github.com/tectova/coverage/blob/main/NOTICE).

The licence does not extend to Tectova's underlying database, person-level records, third-party source material, images or trademarks.

## How to cite

Tectova requests attribution in this form: *Tectova, “[page title],” tectova.com/[path], accessed [date].*

Cite a coverage row to https://tectova.com/shows#archive-coverage and the publication accounting to https://tectova.com/methodology#publication-accounting, not to GitHub. When quoting a figure, retain the geography, category and as-of date displayed on the supporting page. This is a request from Tectova, not an additional condition on reuse under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode).

## What is not here

Person-level data (rankings, casts, profiles, agency representation), show lists, images and source material are not redistributed here. For a tailored cut of the record, see [tectova.com/press](https://tectova.com/press).
