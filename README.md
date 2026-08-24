# Development Economics JMP Blog Archive

## Overview

The Development Economics JMP Blog Archive brings together job-market-paper blog posts published by the World Bank Development Impact blog and Economics That Really Matters. It is designed for searchable exploration of frontier development-economics research featured in these two established sources, descriptive trends in topics, methods, and geographies, and use as a teaching resource.

The archive describes papers featured in these two recurring blog series. It is not a census of all development-economics job market papers.

## Explore the archive

Live site: https://pbiscaye.github.io/devecon-jmp-blog-archive/

Repository: https://github.com/pbiscaye/devecon-jmp-blog-archive

The static site has three pages: Browse archive, Trends, and About. Browse archive provides search, filters, card and table views, and filtered CSV downloads. The Trends page summarizes posts over time, topics, methods, and study geographies. The About page contains the primary download and documentation links.

## Coverage

The archive was launched in August 2026. Version 1.0 contains 310 blog-post occurrences: 260 from World Bank Development Impact and 50 from Economics That Really Matters. The unit of observation is the blog-post occurrence, so cross-posted papers are retained separately.

## What is included

Records include source, academic season, publication date, blog-post title, canonical blog URL, featured author, job-market institution at posting time, author website when available, paper title when available, paper link when available, and classifications for geography, research method, topic, unit of analysis, and study population.

The public/display title is always the blog-post title. Paper links are convenience links checked as of August 2026 and may point to working-paper or published versions.

## Data and downloads

The primary data file is `data/dev_jmp_blogs_archive.csv`. It contains one row per blog-post occurrence. Multi-valued fields use ` | ` as the delimiter. Long-form classification files are available as secondary machine-readable data.

Country classifications are conservative and assigned only when countries are supported by the featured blog post. Broader Multi-country, regional, and Global scope values are used where appropriate.

## Methodology/classifications

See `docs/methodology.md`, `docs/codebook.md`, and `docs/taxonomy.md`. Source blog posts and available paper materials were reviewed systematically across five dimensions: geography, research methods, topics, units of analysis, and study population. LLM/AI assistance supported systematic extraction and classification; human judgment and review resolved classifications and ambiguous cases.

## Updating the archive

The archive is intended to be updated annually after the two blog series' job-market-paper seasons conclude, using the same source-preservation, enrichment, review, and public-output process while preserving existing occurrence IDs.

## Citation

Preferred citation for version 1.0:

Biscaye, Pierre. 2026. *Development Economics JMP Blog Archive*. Version 1.0.

## License

Curated archive data and original documentation are licensed under CC BY 4.0. Website/build/source code is licensed under the MIT License. Blog posts, papers, and other third-party materials linked from the archive remain subject to their respective owners' terms and are not relicensed by this repository.

## Repository structure

- `data/`: public CSV and JSON data files.
- `docs/`: methodology, codebook, and classification definitions.
- `site/`: static website files.
- `LICENSE-CC-BY-4.0.md` and `LICENSE-MIT.md`: license texts.
