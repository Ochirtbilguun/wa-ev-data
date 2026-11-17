# Washington EV Title and Registration Activity

Source: Washington State Department of Licensing, [Electric Vehicle Title and Registration Activity](https://data.wa.gov/Transportation/Electric-Vehicle-Title-and-Registration-Activity/rpr4-cgyd/about_data).

Downloaded: November 17, 2026.

This dataset contains 1,926,507 title and registration transactions. One row is a transaction, not necessarily a unique vehicle.

The original 933.78 MB CSV was converted using DuckDB with normalized column names and Parquet v2 data pages. Snappy produced a 38.13 MB file (95.92% smaller than CSV); Zstandard produced a 30.07 MB file (96.78% smaller). Zstandard was 8.06 MB smaller, so that version is provided.

## Public Parquet download

[ev_zstd.parquet](https://github.com/Ochirtbilguun/wa-ev-data/releases/download/v1.0/ev_zstd.parquet)

The Parquet file is attached to release v1.0. The CSV is not uploaded. Data remains subject to the original provider's terms; no new license for the underlying data is asserted here.
