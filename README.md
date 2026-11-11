# Baltimore Neighborhood Finder

An open-source decision platform for choosing a Baltimore neighborhood to live in.
It compares the city's 279 neighborhoods on things that matter when you move,
like safety, rent, restaurants, and parks, and lets you weight what matters to you.

## Stack

Python (ingest) → DuckDB (warehouse) → dbt (transform) → HTML and Power BI (present)

## Run it

Requires [uv](https://docs.astral.sh/uv/).

```sh
uv sync
cd transform && uv run dbt build
```

## License

Code is MIT licensed. Source data keeps its original terms.
