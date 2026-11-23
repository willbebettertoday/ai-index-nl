# Sysenko AI-index NL, november 2026 / welke bedrijven noemen ChatGPT en Google AI

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24483994.svg)](https://doi.org/10.5281/zenodo.24483994)

## English

Counts of business names in the answers of ChatGPT (with web search), Google AI Overview and Google AI Mode to four fixed Dutch
questions per town, for 18 trades (hairdressers, dentists, estate agents, accountants, mortgage advisers, garages, bakers, butchers,
opticians, kitchen shops, floor shops, bike shops, pet shops, gyms, childcare, hearing-aid shops, physiotherapists, installers).
One measurement, November 2026. 3,185 rows, one CSV per trade, UTF-8, comma separated.

Columns: `trade`, `town`, `measurement` (edition label), `answers_in_town` (AI answers read for the town), `name` (business name as written
in the answer), `answers_with_name` (answers in which it appears), `answers_chatgpt`, `answers_aio` (Google AI Overview), `answers_aimode` (Google AI Mode).

Method: fixed questions, asked through a data provider without account or history; a business counts when the answer writes its name
in the text or on a ChatGPT card; links and sources under the answer do not count; names read by hand; branches of one chain in the same town count as one name.
AI answers change from day to day: this is one measurement, not a ranking and not a judgement of any business. Full method: https://sysenko.com/ai-index/

Licence: CC BY 4.0. Cite as: Sysenko (D.V. Sysenko), "AI-index NL, november 2026", https://sysenko.com/ai-index/ (version 2026.11.0).
Live pages and newer editions: https://sysenko.com/nl/ai-index/plaats/ . Contact and removal requests: danil@sysenko.com (a business name is removed in the next version).

## Nederlands

Aantal antwoorden van ChatGPT (met webzoekfunctie), Google AI Overview en Google AI Mode waarin een bedrijfsnaam staat, bij vier vaste
Nederlandse vragen per plaats, voor 18 branches. Een meting, november 2026. 3.185 rijen, een CSV per branche (UTF-8, komma).

Kolommen: zie hierboven. Een naam telt als het antwoord die in de tekst schrijft of op een ChatGPT-kaartje toont; links en bronnen onder het
antwoord tellen niet. De namen zijn met de hand nagelezen; vestigingen van een keten in dezelfde plaats tellen als een naam.
AI-antwoorden wisselen per dag: dit is een meting, geen ranglijst en geen oordeel over een bedrijf.

Licentie: CC BY 4.0, vermeld "Sysenko (D.V. Sysenko), AI-index NL, november 2026, https://sysenko.com/ai-index/".
Actuele pagina's per plaats: https://sysenko.com/nl/ai-index/plaats/

## Files

- `data/<trade>.csv` x 18 (copies of https://sysenko.com/nl/ai-index/<trade>/data.csv, same bytes)
- `datapackage.json` (Frictionless Data descriptor, schema per file)
- `LICENSE.md`
