# Walmart Weekly Sales Analysis

A project where I looked at 3 years of weekly sales data across 45 Walmart stores
to find patterns in store performance, holidays, seasonality, and what factors
actually affect sales.

## Tools
Python, pandas, NumPy, matplotlib

## Questions I answered
1. Which stores generate the most revenue?
2. Do holiday weeks significantly boost sales?
3. What time of year has the highest sales?
4. Does temperature or fuel price affect weekly sales?
5. Which stores are most consistent vs. most volatile in sales?

## What I did
- Cleaned up the date column and split it into year/month so I could group sales
  by time period
- Compared average sales and standard deviation across stores to see which ones
  were strongest and which were most consistent
- Compared holiday weeks to non-holiday weeks using bar charts and a boxplot to see
  the full spread, not just the average
- Fit trend lines over temperature and fuel price to see if either one actually
  predicts sales

## Key findings
- Stores 4, 13, 14, and 20 are the strongest performers, averaging around $2M/week,
  about 5x more than the weakest stores
- Holiday weeks average about 10% more in sales than non-holiday weeks, but they're
  also less consistent, some holidays drive way more sales than others
- December is the highest-sales month every year, peaking around $285M in 2011
- Temperature has a weak relationship with sales at best, and fuel price barely
  seems to matter at all
- The most consistent stores tend to be lower performers, while the higher-performing
  stores are more volatile, probably more sensitive to promotions or seasonality

## Skills used
Python, pandas (groupby, aggregation), data visualization, trend line fitting,
data cleaning

## Files
  - Walmart_Sales.ipynb — full notebook with code, charts, and analysis
