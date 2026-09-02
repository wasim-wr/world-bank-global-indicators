# world-bank-global-indicators

#🌍  World Bank Global Indicators
Power BI Dashboard Analysis  •  2000 – 2010  •  214 Countries
Health  |  Economy  |  Population  |  Technology  |  Infrastructure
Countries	Time Span	Indicators	Records	Tool
214	11 Yrs	18	2,354	Power BI


1.  Project Objective
To analyse 11 years of World Bank data (2000–2010) across 214 countries and uncover global patterns in economic growth, public health, population dynamics, and digital adoption — visualised through an interactive Power BI dashboard to support data-driven understanding of development trends.


2.  Dataset Overview
Category	Indicators Covered
💰 Finance	GDP (current US$), GDP per capita
🏥 Health	Life expectancy (M/F/Total), Under-5 mortality, Health expenditure (per capita & % GDP)
👥 Population	Total, Urban, Birth rate, Age groups (0–14, 15–64, 65+)
📱 Business	Mobile phone subscribers, Internet users per 100 people
🚆 Transit	Railway passenger-km, Passenger cars per 1,000 people


3.  Process
Data Collection
▸  Source: World Bank Open Data — 214 countries, 2000–2010
▸  Format: Excel (.xlsx) with structured pivot sheets + raw country-year data
Data Cleaning & Transformation
▸  Handled missing values across sparse indicators (railways, cars, GDP)
▸  Standardised date format and country names for consistent filtering
▸  Created calculated columns: age dependency ratio, GDP growth rate, internet penetration tier
Data Modelling (Power BI)
▸  Built star schema: Country dimension + Year dimension + Indicators fact table
▸  DAX measures: YoY GDP growth %, life expectancy gap (F–M), mortality reduction rate
▸  Relationships established across 3 dimension tables
Dashboard Design
▸  5 thematic report pages: Overview, Health, Economy, Population, Technology
▸  Slicers: Country, Region, Year range — all visuals cross-filter dynamically
▸  KPI cards, choropleth maps, line trends, scatter plots, bar comparisons


4.  Business Questions & KPIs Solved

#	Question	Answer / Finding
Q1	Which countries have the highest GDP per capita in 2010?	Luxembourg ($104K), Bermuda ($90K), Norway ($85K) — 3–10× above global avg
Q2	How did global GDP evolve over the decade?	World GDP nearly doubled: $32T (2000) → $62.1T (2010)
Q3	Which countries lead in life expectancy?	Japan & Hong Kong (83 yrs); Nigeria lowest at ~49 yrs
Q4	Where is under-5 child mortality highest?	Mali (178), Burkina Faso (176), Sierra Leone (174) per 1,000 live births
Q5	Does health spending correlate with longer lives?	Moderate positive correlation (r = 0.54) — spending matters but not solely
Q6	How fast did mobile & internet adoption grow?	Mobile: 0.7B → 5.4B subscribers; Internet: 8.4% → 35.5% avg penetration
Q7	Which regions are urbanising fastest?	Global urban pop rose from 2.84B to 3.48B; Asia led urbanisation surge
Q8	Which economies grew fastest (GDP)?	China: $1.2T → $5.9T (5× growth); India and Brazil also major climbers


5.  Dashboard Insights

Page	Visual	Key Insight
Overview	World Map + KPI Cards	GDP and life expectancy show sharp North–South divide across all years
Economy	Line chart + Bar rank	China overtook Japan in total GDP by 2010; emerging markets accelerating
Health	Scatter: Spend vs Life Exp	Sub-Saharan Africa clusters in low-spend/low-longevity quadrant; clear gap from Europe
Health	Mortality trend lines	Under-5 deaths fell in every region — biggest drop in South/East Asia
Population	Age pyramid + Birth rate	Africa has youngest population (45%+ under 14); Japan/Europe aging rapidly
Technology	Area chart: mobile/internet	Mobile saturation near 100% in developed nations by 2008; internet lagging in low-income


6.  Project Insights
🌐 The World Grew Richer — But Unevenly
Global GDP doubled in a decade, yet the gap between top and bottom countries widened. Luxembourg's per-capita income ($104K) was over 1,100× that of the poorest nations.
📱 The Decade of Mobile
Mobile subscribers exploded 7.7× (0.7B → 5.4B). In many developing nations, mobile phones arrived before roads, banks, or clinics — a leapfrog phenomenon visible clearly in the data.
🏥 Health Gains Were Universal, but Slow in Africa
Life expectancy improved globally. However, Sub-Saharan Africa averaged 15–20 years below East Asia and Europe. Under-5 mortality in Mali (178/1,000) versus Japan (<5/1,000) illustrates a stark inequality.
🏙️ Urbanisation is a Mega-Trend
640 million people moved to cities in just 10 years. Rapid urbanisation in Asia and Africa is reshaping labour markets, health infrastructure, and climate exposure.
💡 Health Spending ≠ Health Outcomes Alone
The 0.54 correlation between health expenditure and life expectancy shows money helps — but governance, education, and sanitation also drive outcomes. Some low-spend countries outperform high-spend peers.

China's GDP grew 5× in 10 years — the most dramatic single-country economic transformation visible in the dataset. By 2010 it was closing in on Japan as Asia's economic leader.


7.  Final Conclusion
The 2000–2010 World Bank data tells a story of a world in rapid transition. Technology adoption compressed decades of progress into years. Economies that embraced reform (China, India, Brazil) surged. Health outcomes improved globally, yet Sub-Saharan Africa remained a region of persistent vulnerability.

Three strategic takeaways for policymakers and analysts:
▸  Invest in mobile & internet infrastructure — it is the fastest multiplier of economic access in developing nations.
▸  Targeting child mortality in West/Central Africa (Mali, Chad, Burkina Faso) remains the single highest-impact health intervention.
▸  Economic growth without health investment creates fragile prosperity — GDP and life expectancy must be tracked together.

This dashboard transforms 2,354 rows of raw World Bank data into a navigable, policy-relevant story — demonstrating end-to-end skills in data cleaning, DAX modelling, and interactive Power BI storytelling.

Tools: Power BI  •  Data: World Bank Open Data (2000–2010)  •  github.com/wasim-wr/worldbank-indicators
