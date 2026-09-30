# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). By participating you agree to abide by its terms.

## Scope

This list collects public datasets and key deep learning papers on **mammography** (including DBT and CESM), grouped into Dataset, Classification, Detection/Segmentation, Risk Prediction, and Foundation Model.

## Adding an entry

1. Add your entry to the matching section of [README.md](README.md), keeping each section sorted by year (oldest first).
2. Use the format below. The link text is the paper title only (no tags or acronyms).

   ```markdown
   - [Paper Title](https://doi.org/...) - One-sentence description of what the paper does. Published in Venue (Year). [Code](https://github.com/...).
   ```

   For datasets, link the data and describe it briefly.

   ```markdown
   - [Dataset Name](https://data-url) - Modality, N subjects, Country. Published in Venue (Year). [Paper](https://doi.org/...).
   ```

3. Use the journal volume or issue year, or the conference year for proceedings, in both the README and the BibTeX entry.
4. Link the published version (DOI or publisher page) when one exists. Use the arXiv link only for unpublished preprints.
5. Add the code link only if the repository is the official implementation of the paper. Omit `[Code]` otherwise.
6. Add the BibTeX entry to the matching file in [bib](bib) (for example `bib/classification.bib`), in the same order as the README.
7. Descriptions are one objective sentence: start with a capital letter and end with a period. Check for duplicates and spelling.
8. Open a pull request with one entry (or a few related entries) per PR. Use a title like `Add <paper title>`.

## Updating an entry

If a preprint has been published, replace the link and venue with the published version and update the BibTeX. If a repository turns out to be unofficial or is removed, delete the `[Code]` link.
