NSE Indices Heatmap Dashboard
A modern and interactive Streamlit dashboard for visualizing live NSE (National Stock Exchange of India) indices data. Get instant insights into sector-wise market trends, top gainers/losers, and concise AI-powered summaries for informed decision-making.

Features
Interactive Treemaps: Visualize index composition, market cap, gainers, and losers for any major NSE index.

Advance/Decline Pie Charts: Instantly view market breadth by advances, declines, and no-change stocks.

AI-Powered Market Insights: Summarized daily index outlooks via Groq API—concise, neutral, and data-driven.

Single & Multi-Index Modes: Drill into a single index or compare up to 3 indices side by side.

Key Metrics & Tables: Display market cap, volatility, PE ratios, dividend yields, and top gainers/losers.

CSV Export: Download filtered, raw data for offline analysis.

Live Updates: Auto-refreshes every 5 minutes for the latest market information.

Refined UI/UX: Custom CSS for smooth gradients, shadows, and modern layout.

Screenshots
![Dashboard Screenshot](

(Include your own dashboard image here)

Tech Stack
Streamlit

Plotly

yfinance

Groq LLM API

pandas

Custom CSS

Getting Started
1. Clone the Repository
bash
git clone https://github.com/yourusername/nse-heatmap-dashboard.git
cd nse-heatmap-dashboard
2. Install Dependencies
bash
pip install -r requirements.txt
3. Set Up Groq API Key
Add your Groq API key as an environment variable or in secrets.toml:

text
GROQ_API_KEY = "your_api_key_here"
4. Run the Application
bash
streamlit run app.py
The dashboard will open automatically in your browser.

Usage
Select an index, filter stocks, and explore the treemap and stats.

Switch modes for side-by-side index comparison.

Download CSV for custom analysis.

Read Groq-powered summaries for instant market narratives.

License
MIT License
