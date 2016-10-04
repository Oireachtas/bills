# Houses of the Oireachtas Bill Transformations

Houses of the Oireachtas

This repository contains proof of concept python scripts to convert Oireachtas Bills from ODT format to Akoma Ntoso.

Two Jupiter Notebooks have been added to the repository, the [first](notebooks/bill-odt-v1.pynb) transforms a simple Bill and the [second](notebooks/bill-odt-v2.pynb) transforms a more complex Bill.

Additional Bills are contained in `./data/raw`

## Directory Structure

```
├── data
│   ├── external       <- Bills in pdf format.
│   ├── interim        <- Intermediate data that has been partially transformed or unpacked.
│   ├── processed      <- The final data sets in Akoma Ntoso format.
│   └── raw            <- Bills in their original, odt format.
|
├── notebooks          <- Jupyter notebooks.
```
