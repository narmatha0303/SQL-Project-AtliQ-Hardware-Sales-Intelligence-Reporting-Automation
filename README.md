
# AtliQ Hardware — SQL Sales and Finance Reporting

MySQL portfolio case study covering reusable sales reports, fiscal-year calculations and market performance comparisons.

[Read the project report](SQL%20Project.pdf) · [Open the presentation](https://1drv.ms/p/c/A12F2CA3782F59B4/IQSSPAwwGY_DTYwwgrPrjO2mAYI-j6r8nWqALEus542Wc1I) · [Portfolio](https://codebasics.io/portfolio/Narmatha-Annadurai)

## Business question

How can sales teams answer recurring questions about markets, customers and products without rebuilding the same report each time?

## What I worked on

- Joined sales facts with customer and product dimensions.
- Used aggregations, common table expressions and window functions for comparisons and rankings.
- Created views such as gross sales and net sales.
- Used functions to align transactions with a September-to-August fiscal year.
- Created stored procedures for parameterised reports and market classification, including `get_market_badge`.

## Report coverage

The PDF covers monthly sales, market and customer comparisons, product rankings and reusable reporting logic. Market badge thresholds refer to sold quantity, not dollar revenue. Check the procedure parameters and units in the report before interpreting its output.

## Available files

| File | Purpose |
| --- | --- |
| [SQL Project.pdf](SQL%20Project.pdf) | Analysis and documented SQL examples |
| [SQL course certificate](SQL%20Beginner%20to%20advanced%20Codebasics%20Certification.pdf) | Course completion evidence |

SQL scripts, a database backup and a benchmark log are not currently included. The uploaded report can be reviewed, but this repository alone is not a runnable database project. The earlier 95% reporting-latency claim has no reproducible timing evidence here, so it is not presented as a verified result.

## Tools

MySQL · Stored procedures · User-defined functions · Views · CTEs · Window functions · Star schema

**Narmatha Annadurai** — [LinkedIn](https://www.linkedin.com/in/narmatha-annadurai) · [Portfolio](https://codebasics.io/portfolio/Narmatha-Annadurai)
