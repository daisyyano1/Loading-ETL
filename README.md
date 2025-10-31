1. Project Overview

This project covers the Load phase of the ETL process.
It focuses on loading the cleaned and transformed retail datasets into structured storage formats for reliable access and analysis.

2. Data Source

The data used was obtained from the Transform phase of the Online Retail II dataset and includes:

Transformed full dataset

Transformed incremental dataset

3. Load Implementation

The datasets were successfully loaded into two formats:

SQLite database for relational storage and structured querying.

Parquet files for efficient, columnar storage and fast analytical access.

All files were saved in the loaded directory for organized storage.

4. Verification

The loaded data was reviewed to confirm:

Correct record counts

Accurate column names and data types

No missing or corrupted records

Verification confirmed full consistency with the transformed data.

5. Tools Used

Python • Pandas • SQLite3 • Jupyter Notebook

6. Summary

The Load phase was completed successfully.
The datasets are now securely stored in both SQLite and Parquet formats, ensuring they are analysis-ready and warehouse-compatible.
