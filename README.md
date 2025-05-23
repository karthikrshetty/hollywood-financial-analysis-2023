# 💰 Hollywood Movies Financial Analysis (2023)

This Python project collects and analyzes the financial performance of Hollywood movies released in 2023 using [The Movie Database (TMDb)](https://www.themoviedb.org/documentation/api) API. It focuses on metrics such as budget, revenue, and ROI, providing insights through visualizations.

---

## 🔧 Features

- Fetches movie data from TMDb API (top English-language movies from 2023)
- Extracts financial metrics: budget, revenue, ROI
- Analyzes additional data: runtime, genres, production companies, popularity
- Visualizes:
  - Top 10 highest-grossing movies
  - Revenue vs. Budget
  - ROI distribution by genre
  - Average revenue by production company
- Exports final data to a CSV file

---

## 📦 Requirements

Install the dependencies using:

```bash
pip install requests pandas matplotlib seaborn
