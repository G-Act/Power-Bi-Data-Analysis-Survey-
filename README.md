
# Data Workforce Entry Barriers Dashboard – Power BI Project

(screenshots/dashboard-overview.png)

An interactive Power BI dashboard analyzing real-time survey data from data professionals (Data Scientists, Data Analysts, Data Architects, Database Administrators/Engineers, and related roles). The project explores the key difficulties and barriers people face when entering or breaking into the data workforce.

This dashboard highlights challenges such as lack of experience requirements, competition for entry-level roles, need for advanced skills (SQL, Python, cloud tools), educational barriers.
## Project Overview
- Data Source: Real-time survey collected in CSV format from available data professionals worldwide.
- Objective: Visualize and uncover the main entry difficulties into data careers, helping aspiring professionals understand realistic hurdles and prepare better.
- Key Insights Focus:
  - Most common barriers to entry (e.g., "2–3+ years experience required for junior roles", skill gaps in ML/cloud/SQL, lack of training opportunities).
  - Differences by role (Data Scientist vs Analyst vs Architect vs Database work).
  - Trends in education, tools knowledge, and self-reported difficulty ratings.

## Tech Stack & Process
- Power BI Desktop for modeling, DAX, and visualization
- Power Query for full data cleaning:
  - Removed duplicates & nulls
  - Standardized role titles and responses
  - Handled multi-select questions (split columns, unpivoted where needed)
  - Created calculated columns for grouping difficulties/barriers
- Visuals: Bar/column charts, pie/donut for proportions, treemaps for breakdowns, slicers for role filtering, cards for key stats

## How to Explore
1. Download & Open the [.pbix file](Data-analysis-survey.pbix) in Power BI Desktop (free download from Microsoft).
2. Refresh if you have the source CSV (included or linked).
3. Use slicers to filter by role, difficulty level, region, etc.


## Key Learnings & Challenges Overcome
- Dealing with messy, real-world survey data (inconsistent text responses, multi-value columns).
- Transforming raw CSV into a clean model in Power Query.
- Creating meaningful visuals that tell a story about career entry barriers.
- Highlighting trends: tougher entry-level market, rising demand for practical portfolios over degrees, AI/automation impact on junior roles.

## Why This Project?
The data job market has become more competitive  many "entry-level" postings ask for experience, and companies train juniors less. This dashboard quantifies those frustrations from real professionals' experiences.

Perfect for:
- Aspiring data professionals preparing their learning path
- Career switchers understanding realistic hurdles
- Portfolio showcase of end-to-end Power BI skills (ingest → clean → model → visualize)

Feel free to download, explore, fork, or reach out with questions/feedback!

Connect:  
- LinkedIn: www.linkedin.com/in/enyinnaya-onyekwere-a6528639b
- X/Twitter: @Goshenpalace  
- Email: gospleenyinnaya@gmail.com
Thanks for checking out my work! 
