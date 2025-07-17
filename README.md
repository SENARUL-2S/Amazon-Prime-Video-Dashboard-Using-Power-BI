# 🎬 Amazon Prime Video Dashboard

A visually interactive Power BI dashboard that explores, analyzes, and presents key insights about content available on Amazon Prime Video. The dashboard provides deep insights into show ratings, genres, countries, and trends over time — all in a single glance.

![Dashboard Preview](./your-dashboard-image.png)

---

## 📊 Key Features

- **Total Titles & Directors**: Displays the overall content volume and number of unique directors.
- **Ratings Breakdown**: Visualizes the distribution of content by age ratings (e.g., 13+, 18+, PG-13).
- **Genre Distribution**: Shows the most common genres such as Drama, Comedy, Suspense, etc.
- **Country-wise Show Count**: A map showing how shows are distributed globally.
- **Content Type Split**: Pie chart indicating the proportion of Movies vs TV Shows.
- **Release Year Trend**: Line chart showing the growth of Amazon Prime's library over time.

---

## 📁 Dataset Overview

The dataset contains metadata on Amazon Prime content including:

| Field Name       | Description                                                |
|------------------|------------------------------------------------------------|
| `show_id`        | Unique identifier for each show                            |
| `type`           | Type of content (Movie / TV Show)                          |
| `title`          | Title of the show                                          |
| `director`       | Director(s) of the content                                 |
| `cast`           | Leading actors/actresses                                   |
| `country`        | Country of origin                                          |
| `date_added`     | Date when content was added to Prime Video                |
| `release_year`   | Year the content was originally released                   |
| `rating`         | Audience rating (e.g., 13+, PG, R)                         |
| `duration`       | Length of the movie or number of seasons                   |
| `listed_in`      | Genre categories                                           |
| `description`    | Short description of the content                           |

---

## 📌 Tools & Technologies Used

- **Power BI**: Data visualization and dashboard design
- **Microsoft Excel / CSV**: Data cleaning and transformation
- **Python and pandas**: For preprocessing data

---

## 🧠 Insights Discovered

- **Drama** is the most dominant genre.
- A large percentage (80%+) of content is movies.
- Most content comes from **North America, Europe, and India**.
- Significant growth in content added post-2000.

---

## 🛠 How to Use

1. Open the `.pbix` file using Power BI Desktop.
2. Load the dataset (CSV/Excel).
3. Explore filters such as **Quarter**, **Year**, or **Country** to analyze trends.
4. Customize visuals if needed for personal or organizational insights.

---


⭐ **If you liked this dashboard, give it a star on GitHub!**

