# LinkedIn Content & Engagement Strategy Analysis

**Context**
This project presents a data-driven analysis of LinkedIn content performance, audience engagement and follower dynamics for a B2B legal firm operating in an international logistics context.
All data used in this repository has been fully anonymised.

**Objective**
The goal of the analysis was to evaluate how LinkedIn content contributes to audience growth and engagement, and to develop a measurable, evidence-based content strategy aligned with business goals.

## Scope of Analysis

The project covered three complementary areas:
- **Content performance** (posts and engagement metrics)
- **Audience behaviour** (visitors and followers)
- **Campaign impact assessment** over multiple time periods

The analysis was conducted across **three comparable cohorts**, allowing both baseline comparison and post-campaign evaluation.

## Key Business Questions Addressed

- Which types of content generate higher engagement and click-through rates?
- How does posting frequency and consistency affect visibility and audience growth?
- Are there observable differences between baseline and campaign periods?
- How does content performance relate to changes in visitors and followers over time?
- What level of data volume is required for statistically reliable optimisation?

## Data & Cohort Structure
Three time-based cohorts were analysed:
| Cohort                | Content Period                        | Visitors/Followers Period              |
|-----------------------|---------------------------------------|----------------------------------------|
| **2024_baseline**     | Feb 12, 2024 – Feb 10, 2025            | Apr 14, 2024 – Apr 13, 2025             |
| **2024_same_period**  | Mar 20, 2024 – Apr 20, 2024            | Mar 20, 2024 – Apr 20, 2024             |
| **2025_campaign**     | Mar 20, 2025 – Apr 20, 2025            | Mar 20, 2025 – Apr 20, 2025             |

This structure enabled controlled comparison between organic activity and campaign-driven content.

## Analytical Approach

## 1. Content Performance Analysis

- Time-series analysis of impressions, clicks, engagement rate and CTR
- Comparison of performance distributions across cohorts
- Identification of outliers and performance variability
- Weekday-based performance patterns

## 2. Audience Analysis

- Trends in new visitors and followers
- Growth rate comparisons across cohorts
- Segmentation by country, industry, company size, job function and seniority
- Identification of dominant audience segments

## 3. Content–Engagement Relationship

- Alignment of posting dates with visitor and follower peaks
- Lag and cross-correlation analysis to detect indirect content impact
- Noise reduction via moving averages

## Key Insights

- With limited posting volume, observed performance differences are directionally positive but not yet statistically robust
- Content consistency and frequency are critical drivers of visibility
- Certain weekdays show systematically higher median CTR
- Audience growth patterns suggest indirect effects of content rather than immediate spikes
- Reliable predictive modelling requires a higher and more stable content volume

## Strategic Recommendations

- Increase posting frequency to 3 posts per week to reach statistically reliable sample sizes within 4–6 months
- Standardise posting days and formats to reduce noise
- Expand tracked features (format, text length, posting time, audience segment)
- Continue descriptive monthly reviews focusing on medians and confidence intervals
- Plan predictive modelling and A/B testing once sufficient data volume is achieved

## Deliverables

- Dashboard-ready charts and analytical tables
- Management-level slide deck with narrative insights
- Actionable content strategy roadmap aligned with business objectives

## Role & Skills Demonstrated

**Role: Project Lead**
- Business-oriented data analysis and KPI interpretation
- Strategic content and audience segmentation
- Translating analytics into clear management recommendations
- Structuring long-term optimisation roadmaps

## Tools & Methods (Technical Appendix)

- **Data analysis:** Python (pandas, numpy, scipy)
- **Statistics:** non-parametric testing, bootstrap confidence intervals
- **Time series:** trend analysis, cross-correlation, moving averages
- **Visualisation:** Matplotlib, Seaborn, PowerPoint
- **Data privacy:** anonymisation best practices

## Repository Structure
| Folder     | Description                                    |
|------------|------------------------------------------------|
| [Analysis](https://github.com/MarinaDataAnalyst/LinkedIn_Content_Management/tree/main/analysis) | Jupyter notebooks with initial data audits, cohort comparisons after launching posting campaign, statistical tests, and final results |
| [LinkedIn_Content_&_Engagement_Strategy_Analysis](https://github.com/MarinaDataAnalyst/LinkedIn_Content_and_Engagement_Strategy_Analysis/blob/main/analysis/LinkedIn_Content_%26_Engagement_Strategy_Analysis.pdf)| Presentation with insights, charts and suggested actions |


