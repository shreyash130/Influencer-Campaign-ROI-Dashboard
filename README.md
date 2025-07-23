
# Influencer Campaign ROI Dashboard

![Dashboard Preview] ((https://github.com/shreyash130/Influencer-Campaign-ROI-Dashboard/blob/main/streamlit-influencer_dashboard-2025-07-21-12-07-28-ezgif.com-video-to-gif-converter.gif)

Optimise influencer marketing ROI across HealthKart brands with granular insights & dynamic reports.*

## 🚀 Overview

The **Influencer Campaign ROI Dashboard** is a powerful tool to analyse, measure, and visualise the performance of influencer marketing campaigns. Designed for HealthKart’s multi-brand setup, it provides:

- Deep-dive, granular insights at the influencer, campaign, brand, and product levels  
- Dynamic filtering by brand, product, persona, and platform  
- ROI & incremental ROI calculations with customizable baselines  
- Engagement tracking (reach, likes, comments) per post  
- Automated highlights to identify top performers and underperformers  
- Interactive charts and downloadable reports (CSV & PDF)  
- Easy-to-use, responsive Streamlit interface

## ⚡ Features

| Feature                 | Description                                                                                     |
|-------------------------|-------------------------------------------------------------------------------------------------|
| **Data Upload**         | Upload multiple CSV files: `influencers.csv`, `posts.csv`, `tracking_data.csv`, `payouts.csv`.  |
| **Dynamic Filters**     | Filter data by brand, product, persona type, gender, follower count, and platform.               |
| **Granular Analytics**  | Analyse metrics at every level: influencer, campaign, brand, and product.                        |
| **ROI & Incrementality**| Calculate ROAS & incremental ROAS (true lift over baseline).                                   |
| **Engagement Tracking** | Visualise post reach, likes, and comments.                                                     |
| **Automated Insights**  | Instantly find top influencers, best personas, and campaigns with poor ROI.                     |
| **Charts & Exports**    | Interactive Plotly graphs with export options in CSV and PDF formats.                           |
| **User-friendly UI**    | Intuitive sidebar controls and responsive Streamlit layout for seamless usage.                 |

## 📦 Getting Started

### 1. Clone or Download  
```bash
git clone https://github.com/shreyash130/influencer-campaign-roi-dashboard.git
cd influencer-campaign-roi-dashboard
```

### 2. Install Dependencies  
Use the provided requirements file for quick setup:
```bash
pip install -r requirements.txt
```

### 2.2 Also compatible with:

```bash
pip install streamlit pandas plotly matplotlib numpy
```

### 3. Launch the Dashboard  
```bash
streamlit run influencer_dashboard.py
```

### 4. Upload Your Data  
On the sidebar, upload the required CSV files:  
- `influencers.csv`  
- `posts.csv`  
- `tracking_data.csv`  
- `payouts.csv`

Use sidebar filters to explore your data across brands, products, personas, and platforms.

## 📂 CSV Data Format

| CSV File          | Key Columns                                                                                     |
|-------------------|-------------------------------------------------------------------------------------------------|
| `influencers.csv` | `id, name, category, gender, followers, platform`                                               |
| `posts.csv`       | `influencer_id, platform, date, url, caption, reach, likes, comments`                            |
| `tracking_data.csv` | `source, campaign, influencer_id, user_id, brand, product, date, orders, revenue`               |
| `payouts.csv`     | `influencer_id, basis, rate, orders, total_payout`                                              |

*Sample CSV files are included for quick testing.*

## 🔍 Insights & What You Get

- **ROI Metrics:** Revenue generated per ₹ spent on influencer campaigns  
- **Incremental ROAS:** True ROI considering user-defined revenue baselines  
- **Top & Poor Performers:** Identify winning influencers and campaigns fast  
- **Engagement Breakdown:** Compare reach, likes & comments across platforms  
- **Exportable Reports:** Download ready-to-share CSV and PDF reports  

## 💡 Why Use This Dashboard?

- Make influencer marketing ROI **actionable and transparent**  
- Save hours with **automated reporting and insights**  
- Easily **customise data inputs and filters** as your marketing programs evolve  
- Communicate results clearly with **interactive visuals and exports**

## 🙌 Contributions & Feedback

I welcome your issues, bug reports, and pull requests! Feel free to contribute or suggest new features by opening an issue.

## 👤 Author

**Shreyash Raj**  
[LinkedIn](https://www.linkedin.com/in/shreyashraj130596) | [GitHub](https://github.com/shreyash130)

## 🚀 Get Started Now!

Upload your campaign data and turn your influencer marketing into measurable, optimised ROI in seconds!

*Built with ❤️ using Streamlit, Pandas, and Plotly.*

*If you want me to add badges (build status, license, etc.) or a GIF screenshot, just let me know!*
