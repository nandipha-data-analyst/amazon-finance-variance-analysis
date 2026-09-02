## Amazon-Style Financial Variance Analysis
Intern Project | Cape Town, South Africa | Amazon Finance Bar Raiser Ready

## Objective:
Analyze budget vs. actual financial performance, identify key variances >10%, and provide data-driven insights for leadership decisions.

## Project Structure
- data/ - Raw budget vs actual data (CSV)
- notebooks/ - Python analysis (pandas, variance calculation)
- dashboard/ - Excel dashboard with 4 sheets: Detail, Totals, Executive, Pivot_Analysis | VLOOKUP, SUMIFS, Conditional Formatting, Slicers
- sql/ - SQL validation queries (GROUP BY, HAVING, drill-down to transaction level)

## Tools Used
Excel: PivotTables, VLOOKUP, Variance formulas, Conditional Formatting, Charts, Slicers (Self-Serve Analysis)
SQL: GROUP BY Category, HAVING ABS(variance%) > 10%, SUM() for reconciliation
Git: Version control demonstrating Ownership LP

## Key Insight (Dive Deep Example)
Marketing March variance 12.5% overspend flagged via SQL HAVING filter → drilled to transaction level → root cause identified.

## How to Use
1. Open dashboard/Amazon Finance Variance Dashboard.xlsx
2. Use Pivot_Analysis sheet with Category slicer for self-serve
3. Validate totals with sql/variance_queries.sql
