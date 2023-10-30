
# Data Cleaning Exercise

## The Task

With the PDFs provided, find the unique items in the chemical names in each list.

I suppose this is the worse case scenario where the tabular datas are polluted - Names are spelt differently, some have random notes in them so it's not gonna be a A != B.

## The Approach

I attempted to use NLP to filter but it resulted in unneccessary overcomplication. At the end just use TheFuzz library to fuzzy match the all the related entries.

## Requirements

- Python 3.8.18 (Due to TensorFlow)
- pdfplumber (For PDF extraction)
- TheFuzz (For fuzzy matching)
- Pandas (For data manipulation)
- openpyxl (For Excel export)
