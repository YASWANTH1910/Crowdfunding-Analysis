# Crowdfunding-Analysis

# Project Overview
This project analyzes crowdfunding campaigns using real-world data from Kickstarter. The aim is to gain insights into campaign performance, identify success factors, and provide actionable insights for future projects. The analysis covers:
- Project outcomes based on location, category, and time.
- Successful projects’ funding, backers, and duration.
- Top successful projects by backers and amount raised.
- Success rates overall, by category, time, and goal range.

# Dataset Description
The dataset includes information on over 100,000 Kickstarter campaigns with the following key columns:
- **id**: Unique identifier for each project
- **state**: Project status (e.g., successful, failed)
- **created_at, deadline, launched_at**: Timestamps for project lifecycle
- **goal, static_usd_rate**: Funding goal and currency exchange rate
- **backers_count**: Number of backers
- **category_id, location_id**: Project category and location

# Analysis Objectives
1. **Projects Overview KPI**
   - Total projects by outcome, location, category, and time
2. **Successful Projects Analysis**
   - Amount raised, number of backers, and duration
3. **Top Successful Projects**
   - Based on backers and amount raised
4. **Success Rate Analysis**
   - Overall success rate
   - By category, time, and goal range

# Visualizations
Visualizations were created using Matplotlib and Seaborn, including:
- Bar plots for KPI comparisons
- Pie charts for success percentages
- Line plots for trend analysis

# Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab

# Business Insights
- Projects with clear goals and effective reward systems are more successful.
- Categories like Technology and Games have higher success rates.
- Campaigns launched in certain months/quarters tend to perform better.

# About Kickstarter
Kickstarter is a crowdfunding platform enabling creators to fund projects through community support. Successful campaigns reward backers, and the platform charges a fee for successful funding.

# Future Enhancements
- Analyze text descriptions using NLP for sentiment analysis.
- Implement machine learning models for success prediction.



