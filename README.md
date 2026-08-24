# Development Economics JMP Blog Archive

## Overview

The Development Economics JMP Blog Archive brings together job market paper posts published by the World Bank's Development Impact blog and Economics That Really Matters. It is designed for browsing, teaching, and research exploration of papers featured in these two series, including trends in topics, methods, and geographies over time. It is not a census of all development economics job market papers.

## Explore the archive

The static site in `site/` has three pages: Browse archive, Trends, and About. Browse archive provides search, filters, card and table views, and filtered CSV downloads. The About page contains the primary download and documentation links. The site is intended to be served over HTTP, including GitHub Pages-style hosting from a repository subdirectory.

## Coverage

The archive was launched in August 2026. The current release contains 310 blog-post occurrences: 260 from World Bank Development Impact and 50 from Economics That Really Matters. Cross-posts are retained separately.

## Local preview

Do not double-click `site/index.html` or open it directly with a `file://` URL. Most browsers block local JavaScript from loading the site's JSON data files that way.

From the repository root, run:

```bash
python -m http.server 8000 -d site
```

Then open `http://localhost:8000/`.

To preview the staged public repository layout instead, run:

```bash
python -m http.server 8000 -d public_repo
```

Then open `http://localhost:8000/site/`.

## Trends

The Trends page includes four static visualizations: blog posts over time by source, research-topic counts, research-method shares over time, and a country choropleth. Methods and topics can be multi-valued, so seasonal shares need not sum to 100%.

## Data/download

The primary file is `data/dev_jmp_blogs_archive.csv`. It contains one row per blog-post occurrence. Multi-valued fields use ` | ` as the delimiter. Machine-readable long-form classification files are provided as secondary documentation/data. Downloads and documentation links are listed on the About page.

## Variables/classifications

Records include source, season, date, blog-post title, featured author, job-market institution, author website, paper title and paper link when available, and reviewed classifications for geography, research method, topic, unit of analysis, and study population.

## Methodology

See `docs/methodology.md`. The original blog post is the primary source record. Paper links are convenience links checked as of August 2026 and may point to working-paper or published versions.

## Updating the archive

Future job-market seasons should be appended annually after the two blog series' job-market-paper seasons conclude, using the same source-preservation, enrichment, review, and public-output process while preserving existing occurrence IDs.

## Repository link

The public GitHub repository URL is pending: #

## Citation

Final citation wording and release DOI are pending. Use `CITATION.cff` as a placeholder until publication.

## License

Curated archive data and original documentation are licensed under CC BY 4.0. Website/build/source code is licensed under the MIT License. The licenses apply to this archive's original data, documentation, and code. Blog posts, papers, and other third-party materials linked from the archive remain subject to their respective owners' terms and are not relicensed by this repository.

## Repository structure

- `data/`: public CSV and JSON data files.
- `docs/`: methodology, codebook, and classification definitions.
- `site/`: static website files.
- `LICENSE-CC-BY-4.0.md` and `LICENSE-MIT.md`: license texts.
