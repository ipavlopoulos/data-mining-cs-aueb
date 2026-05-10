# Papyri.info Crawler

Web crawler / XML parser for the [idp.data](https://github.com/papyri/idp.data) repository.

## Results

| Field | Value |
|-------|-------|
| Total records | 70,448 |
| With full metadata | 68,032 |
| Without metadata | 2,416 |

## How to Run

1. Open `papyri_crawler.ipynb` in Google Colab
2. Run all cells
3. Results saved in `papyri.csv`

## Extracted Fields

| Field | Description |
|-------|-------------|
| `title` | Document title |
| `filename` | File identifier |
| `hgv` | HGV id |
| `languages` | Languages in the document |
| `date_text` | Date (e.g. "1st century BC") |
| `date_from` | Numeric start date |
| `date_to` | Numeric end date |
| `place` | Findspot |
| `text` | Papyrus text |

## License

Data from papyri.info is available under [Creative Commons Attribution 3.0](http://creativecommons.org/licenses/by/3.0/).
