# reddit-social-media-analytics
End-to-end Reddit data pipeline: Extraction, sentiment analysis, and dashboard visualization using Python &amp; Looker Studio
# Reddit Social Media Analytics Pipeline

This project builds an automated pipeline to:
- Extract Reddit posts and comments via Reddit API (PRAW)
- Clean and analyze post text for sentiment (TextBlob)
- Export data and create interactive dashboards with Looker Studio

## Dashboard Preview

![Dashboard Overview](screenshots/dashboard_overview.png)

## How It Works

1. **Extraction:** Reddit posts and comments are programmatically fetched from selected subreddits.
2. **Transformation:** Data is cleaned, sentiment labelled (Positive/Negative/Neutral), and engagement scored.
3. **Visualization:** Key insights (sentiment distribution, posts over time, top posts) shown with Looker Studio.

## Tech Stack
- Python, Colab
- Libraries: PRAW, pandas, TextBlob
- Visualization: matplotlib, Google Looker Studio

## How to Run
1. Clone this repo.
2. Upload your Reddit API credentials (see notebook).
3. Run the notebook to extract and analyze data.
4. Export results and connect the CSV to Looker Studio using the provided dashboard template.
5. Customize visuals as desired.

## Screenshots

![Sentiment Chart](screenshots/sentiment_chart.png)
![Top Posts Table](screenshots/top_posts_table.png)

## Sample Insights

> "Most posts about AI in r/technology were positive during August 2025."
> "Peak posting times were evenings (IST); top posts saw 200+ comments."

---

### 4. Upload Your Files
- Use GitHub’s web interface or `git` commands to upload your notebook, CSV, and screenshots.
- Make a folder for images/screenshots and link to them in your README.

---

### 5. (Optional) Pin the Repo to Your GitHub Profile
- Go to your profile, “Customize your pinned repositories,” and select this project to feature it.

---

### 6. (Optional) Add Badges/Links
- Add a “View Dashboard” link, if you published your Looker Studio dashboard as public/read-only.

---

## Sample Repo Structure

