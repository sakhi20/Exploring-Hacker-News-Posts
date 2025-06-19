# Exploring Hacker News Posts 📊

This project analyzes user-submitted posts on [Hacker News](https://news.ycombinator.com/) using Python and Jupyter Notebook. The goal is to explore how post type and timing affect user engagement — measured by both **comments** and **upvotes (points)**.

---

## 🎯 Goals

- Compare **Ask HN** and **Show HN** posts based on:
  - Average number of comments
  - Average number of upvotes (points)
- Determine **what time of day** leads to the highest engagement
- Visualize engagement trends using **Matplotlib**

---

## 🛠 Tools Used

- Python
- Jupyter Notebook
- `datetime` module
- Lists, loops, dictionaries
- Matplotlib

---

## 📁 Files

- `hacker_news_analysis.ipynb` — Complete Jupyter Notebook with full code and output
- `hacker_news.csv` — [Downsampled dataset from Dataquest](https://www.dataquest.io/blog/data-science-project-hacker-news/) (only if redistribution allowed)

---

## 📈 Key Insights

### 🧵 Comments Analysis
- **Ask HN posts receive more comments on average** than Show HN posts
- The best time to post an Ask HN post for maximum comments is **3 PM UTC**

### 📊 Upvote (Points) Analysis
- Show HN posts tend to receive **more upvotes** than Ask HN posts
- However, Ask HN posts posted at specific hours can also perform well
- **Top hours for points (UTC):**
  - 15:00 – XX avg points
  - 02:00 – XX avg points
  - 20:00 – XX avg points

> Full analysis and sorted tables included in the notebook

---

## 📉 Visualizations

- **Bar chart**: Average Ask HN points by post hour (UTC)
- Visualizations created using **Matplotlib**
- Easy to interpret the best posting times

---
