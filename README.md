# Food Price Inflation in Nigeria

Food inflation in Nigeria eased through 2025, reached 8.89% in January 2026, and then rose again to 16.96% by May 2026. I wanted to understand what was happening beneath that reversal: which foods changed the most, whether some food categories moved differently from others, and whether factors such as exchange rates and petrol prices were associated with the movement.

## Research Question

How did food prices in Nigeria change from January 2025 to May 2026, which foods and food categories changed the most during the period, and which potential economic factors were associated with the reversal in food inflation?

## Why I Did This

Food prices are something I notice regularly, so I became curious about the pattern behind those changes.

Food inflation had been easing through 2025, but after reaching 8.89% in January 2026, it began rising again. I wanted to look beyond that headline number and investigate what was happening at the individual food and category level, then explore whether some economic factors moved alongside food inflation during the reversal.

## Study Period

**January 2025 – May 2026 (17 months)**

I chose this period because it captures both sides of the change: the decline in food inflation through 2025 and the reversal that began in early 2026.

## What I Analyzed

- Headline inflation compared with food inflation
- Prices of 42 individual food items
- Percentage price changes across the 42 foods
- Broad food-category movements
- The January–May 2026 reversal
- Exchange-rate and petrol-price movements
- Correlations between food inflation and potential drivers
- An exploratory regression during the reversal period

## Data

The analysis uses publicly available Nigerian data from:

- **National Bureau of Statistics (NBS)** — headline and food inflation
- **NBS Selected Food Price Watch** — individual food prices
- **NBS** — petrol price data
- **Investing.com** — monthly closing USD/NGN exchange rates

## Key Findings

- Food inflation behaved differently from headline inflation during the study period.
- Food inflation fell to **8.89% in January 2026**, then rose to **16.96% by May 2026**.
- The 42 food items showed substantial differences in their price movements.
- **Vegetables** had the largest average price change during the January–May 2026 reversal.
- Over the full 17-month period, petrol price showed almost no relationship with food inflation (correlation of **0.001**). During the five-month reversal window, the correlation was **0.93**. This difference between the full-period and reversal-period results was one of the more interesting findings of the analysis.
- During the reversal period, petrol price showed a much stronger statistical association with food inflation than the exchange rate.
- These relationships are observational and **do not establish causation**.

## Limitations

- The study covers only 17 months.
- The reversal-period regression uses only five monthly observations, so its results are exploratory.
- The exchange-rate series is a market-quoted proxy rather than an official CBN series.
- Only two potential drivers were tested.
- Other factors, such as weather, insecurity, supply conditions, and global commodity prices, were not included.

## Notebook

The full analysis, data preparation, visualizations, and statistical analysis are available in the Jupyter Notebook in this repository.
