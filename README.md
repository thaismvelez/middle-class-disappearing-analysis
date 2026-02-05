# Is the American Middle Class Disappearing? A Data Jam Analysis

## Project Overview
This Data Jam competition project evaluates the claim that the American middle class is disappearing. Working with a teammate under a tight deadline, we analyzed economic indicators related to employment, income, spending, and household wealth to understand what’s really changing. Our conclusion is that the middle class is shifting and adapting rather than vanishing. While inequality and affordability challenges are real, this project focuses on separating how things feel from what the data supports, and using evidence to distinguish short-term stress from long-term collapse.

## Data Sources (FRED + TripleTen)
Utilized a mix of datasets from the Federal Reserve Economic Data (FRED) and a spreadsheet provided by TripleTen. For the TripleTen data, the file was imported into Tableau, custom line charts were created, and the visuals were organized into a dashboard for the presentation. For the FRED data, the official line charts from the FRED website were incorporated in the same order as the slide deck.

- **[Real Median Household Income](https://docs.google.com/spreadsheets/d/1eG0uk81Oyp_QFfgJA54nWVZnHO_kijykaRymiJKTVHE/edit?usp=sharing):** Tracks the inflation-adjusted income of the typical U.S. household over time.
- **[Gini Index](https://docs.google.com/spreadsheets/d/1eG0uk81Oyp_QFfgJA54nWVZnHO_kijykaRymiJKTVHE/edit?usp=sharing):** Measures how unequal income distribution is in the U.S.; higher values mean more inequality.
  
- **Labor Force Participation Rate — Men [LNS11300001](https://fred.stlouisfed.org/series/LNS11300001):** Shows the share of men who are working or actively looking for work.
- **Labor Force Participation Rate — Women [LNS11300002](https://fred.stlouisfed.org/series/LNS11300002):** Shows the share of women who are working or actively looking for work.
  
- **Employment-Population Ratio [EMRATIO](https://fred.stlouisfed.org/series/EMRATIO?utm_source=chatgpt.com#):** Shows the percentage of the population that is employed, capturing overall job attachment.
- **Real Median Household Income [MEHOINUSA672N](https://fred.stlouisfed.org/series/MEHOINUSA672N):** Tracks the inflation-adjusted income of the typical U.S. household over time.

- **Real Disposable Personal Income per Capita [A229RX0](https://fred.stlouisfed.org/series/A229RX0):** Tracks inflation-adjusted after-tax income per person, or what people have available to spend or save.
- **Real Personal Consumption Expenditures per Capita [A794RX0Q048SBEA](https://fred.stlouisfed.org/series/A794RX0Q048SBEA):** Tracks inflation-adjusted spending per person, showing how consumption changes over time.

- **Net Worth Held by the Bottom 50% [WFRBLB50107](https://fred.stlouisfed.org/series/WFRBLB50107):** Shows how total wealth owned by the bottom half of households has changed over time.
- **Median Consumer Price Index [MEDCPIM158SFRBCLE](https://fred.stlouisfed.org/series/MEDCPIM158SFRBCLE):** Tracks “typical” inflation by focusing on the median price change across categories.

- **Equities Held by the 50th–90th Percentiles [WFRBLN40068](https://fred.stlouisfed.org/series/WFRBLN40068#):** Shows the total value of stock and mutual fund holdings for upper-middle wealth households.
- **Share of Equities Held by the 90th–99th Percentiles [WFRBSN09149](https://fred.stlouisfed.org/series/WFRBSN09149#):** Shows what portion of all equities is owned by the affluent (excluding the top 1%), highlighting concentration near the top.

## Introduction
Headlines often claim the American middle class is “disappearing.” In this project, we test that claim using data on work patterns, purchasing power, spending behavior, and household financial position. Our findings suggest the middle class is shifting and adapting—not simply vanishing.

We acknowledge rising inequality and real affordability challenges, but perception—how it feels—doesn’t equal disappearance. Our goal is to use data to separate stress from collapse.

## Project Objectives
1. **Evaluate the claim** that the American middle class is disappearing by analyzing trends in income, inequality, employment, spending, and wealth.
2. **Compare long-term patterns and major economic shocks** to understand what changed, what recovered, and what appears structural versus temporary.
3. **Explain the perception gap** by connecting affordability pressure and inequality to why the middle class can feel weaker even when key indicators show strength.
4. **Deliver a clear, story-driven presentation** with a Tableau visual and FRED charts that support a data-backed conclusion.

## Methodology 
1. **Data Collection:**
    - Utilized a TripleTen-provided spreadsheet for median household income and the Gini Index, then imported it into Tableau.
    - Pulled additional economic indicators from FRED and used the official FRED charts in the presentation.

2. **Data Preparation (Tableau):**
    - Cleaned and formatted the TripleTen dataset for time-series analysis.
    - Created line charts and combined them into a Tableau dashboard for side-by-side comparison.

3. **Trend Analysis:**
    - Analyzed long-term patterns across employment, labor participation, income, spending, wealth, and inequality.
    - Identified key turning points around major economic shocks to separate temporary dips from longer-term trends.

4. **Cross-Indicator Comparison:**
    - Compared indicators together (e.g., work participation vs. median income, wealth growth vs. price pressure) to evaluate whether the middle class is shrinking or shifting.
    - Used inequality measures to explain how top-end gains can change perception even when the median improves.

5. **Storytelling & Presentation:**
    - Converted the analysis into slide-ready insights with concise takeaways for each chart.
    - Delivered a final conclusion focused on whether the middle class is disappearing or adapting based on the combined evidence.
  
## Visual Representations
The project findings are presented in a slide deck that includes the key visualizations used in our analysis. The presentation features Tableau-built charts from the TripleTen dataset and selected line charts sourced directly from FRED to support our conclusions.

**Slide Deck:** [“The American middle class is disappearing.” Data Analysis](https://docs.google.com/presentation/d/1T7j3NIEtr-6_r88Ms5vw8pwD0pECmbwzQlRyO3tWHks/edit?usp=sharing)

**Tableau Dashboard:** [Median Income vs Inequality](https://public.tableau.com/app/profile/sergey.zavyalov/viz/TheAmericanmiddleclass/Dashboard1?publish=yes)


## Key Findings
1. **Resilience in the Data:** Data shows income, consumption and wealth strength over time.
2. **Upward Mobility Pipeline:** As lower-income households build more wealth, more of them can move into the lower end of the middle class, so the middle class grows instead of shrinking.
3. **Cost Pressure vs. Reality:** Higher prices on necessities reduced day-to-day breathing room, fueling the perception that the middle class is fading supporting the idea that perception does not equal disappearance.


## Conclusion
The analysis supports that the American middle class is shifting and adapting, not disappearing. Across income, spending, and wealth indicators, the long-term trend shows resilience, while rising essential costs and inequality help explain why it can feel like decline.


## Future Direction

1. **Regional and demographic breakdown:** Slice results by region, household size, and age group, since the meaning and experience of “middle class” varies based on where and how people live.
2. **Essentials vs non-essentials:** Break spending into categories (housing, healthcare, education vs discretionary) to show where the squeeze is coming from.
3. **Wealth composition:** Separate net worth into home equity vs stocks vs cash/debt to see what’s driving gains and how stable they are.
4. **Cohort and life-stage analysis:** Compare outcomes for younger vs older households (e.g., Millennials vs Gen X) to capture differences in affordability and asset-building timing.
