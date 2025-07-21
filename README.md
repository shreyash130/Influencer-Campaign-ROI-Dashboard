# Influencer-Campaign-ROI-Dashboard


Analyse and visualise the effectiveness of influencer marketing campaigns for multiple HealthKart brands, with granular insights, flexible filters, and one-click reporting.

Features
Data Upload: Import campaign data from influencers.csv, posts.csv, tracking_data.csv, payouts.csv.

Dynamic Filtering: Slice analytics by brand, product, persona type (category, gender, follower range), and platform.

Granular Analysis: Examine performance at influencer, campaign, brand, and product level.

ROI & Incrementality: Calculate both ROAS and incremental ROAS (lift over baseline) with user-set baselines.

Engagement Tracking: Visualize post reach, likes, and comments.

Automated Insights: Instantly see top performers, best personas, and poor ROIs.

Charts & Exports: Download filtered results as both CSV and PDF; view colorful interactive graphs with Plotly.

User-friendly UI: Intuitive Streamlit layout with sidebar controls and responsive design.

Setup
1. Clone the Repo or Download Files
text


(or upload all files to your own GitHub repo and then download)

2. Install Dependencies
Recommended: Use the included requirements.txt file for easy setup.


pip install streamlit pandas plotly matplotlib


text

pip install -r requirements.txt


Dependencies:

streamlit

pandas

numpy

matplotlib

plotly

3. Launch the Dashboard
text


streamlit run influencer_dashboard.py


4. Upload Data
On the sidebar:

Upload all four CSV files:

influencers.csv

posts.csv

tracking_data.csv

payouts.csv

Use the sidebar filters to select brands, products, persona types, and platforms for analysis.

Data Model
Example CSV Schemas:

influencers.csv:
id, name, category, gender, followers, platform

posts.csv:
influencer_id, platform, date, url, caption, reach, likes, comments

tracking_data.csv:
source, campaign, influencer_id, user_id, brand, product, date, orders, revenue

payouts.csv:
influencer_id, basis, rate, orders, total_payout

Note: Sample CSVs included for quick testing.

Insights & Outputs
ROI: Revenue generated per ₹ spent on each influencer/campaign.

Incremental ROAS: True ROI after subtracting a business-defined revenue baseline.

Top Influencers/Personas: Instantly see who’s best (or worst) for your KPIs.

Post Engagement: Compare reach, likes, comments across campaigns and platforms.

Downloadable Reports: Export detailed dashboards as CSV or PDF.

Documentation & Storytelling
Each section explains and visualizes results for easy business interpretation.

Exports and visual leaderboards enable clear communication with stakeholders.

Extensibility
Add more brands, platforms, or influencer types as you grow.

Built for adaptation—swap in your own data, tweak filters, or add new fields as needed.


Author
Shreyash Raj
https://www.linkedin.com/in/shreyashraj130596
https://github.com/shreyash130

Feedback & Collaboration
Questions, bugs, or ideas? Open an issue or pull request!

Ready to turn influencer marketing into measurable ROI? Upload your data and get actionable insights in seconds!
