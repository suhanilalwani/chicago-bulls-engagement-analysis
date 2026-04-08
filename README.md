# chicago-bulls-engagement-analysis
Time series analysis of Chicago Bulls social media engagement vs on-court performance 2018–2023 — with NBA sponsorship campaign timing recommendations

# Chicago Bulls — Social Engagement & Performance Analysis

## Business Problem
NBA sponsors spend millions activating campaigns uniformly 
throughout the season. But fan engagement is not uniform — 
it spikes dramatically around wins, player milestones, and 
key moments. This project answers:

> "When does the Chicago Bulls brand generate maximum social 
> buzz — and how should a sponsor time their campaigns to 
> ride those peaks for maximum ROI?"

## Key Findings
1. Winning weeks generate **~20%** higher search interest 
   than losing weeks — sponsors should double content 
   investment immediately after wins
2. The seasonal pattern shows engagement peaks in 
   **October** (season opener) and **April** (playoff push) 
   — the optimal windows for campaign launches
3. The COVID bubble season (2019–21) showed **slightly lower**
   engagement despite no live crowds — proving digital fan engagement is increasingly independent 
   of physical attendance

## Sponsor Campaign Recommendations
1. **Post-Win Amplification**: Activate sponsored content 
   within 2 hours of a Bulls win — engagement is ~1.2× higher
2. **Season Opener Push**: Launch major campaigns in the 
   first 2 weeks of October when interest spikes annually
3. **Player Milestone Events**: Monitor for individual 
   performance milestones — these generate the largest 
   residual spikes in the decomposition analysis

## Tools & Methods
Python (pandas, matplotlib, statsmodels) · MySQL · 
Microsoft Excel · Microsoft Power BI · 
Time Series Decomposition · Correlation Analysis · 
nba_api (official NBA statistics)

## Data Sources
- Game performance: NBA Stats API via nba_api library 
  (official NBA data)
- Social engagement: Google Trends search interest index 
  (industry-standard brand interest proxy)
