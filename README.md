# Book Genre Data Analysis Using Python

## Project Overview

This project investigates how book page counts differ across three literary genres: romance, fantasy, and mystery.

Using Python and data retrieved from the Open Library API, I collected, cleaned, analyzed, and visualized book records to identify patterns in page counts across genres.

## Technologies Used

- Python
- Pandas
- Matplotlib
- SciPy
- Jupyter Notebook
- Open Library API

## Dataset

- **Source:** Open Library API
- **Initial records:** 600 books
- **Cleaned records:** 590 books
- **Genres:** Romance, Fantasy, Mystery
- **Collection date:** October 2, 2026

## Methodology

1. Collected book information through the Open Library API.
2. Cleaned the dataset by addressing missing page counts and examining duplicate records.
3. Calculated descriptive statistics for each genre.
4. Created boxplots to compare page-count distributions.
5. Used Pearson correlation to explore the relationship between publication year and page count.

## Key Findings

| Genre | Median Page Count |
|---|---|
| Fantasy | 440 |
| Mystery | 248 |
| Romance | 191 |

Fantasy books had the highest median page count of the three genres.

A Pearson correlation analysis also found a positive association between publication year and page count (r ≈ 0.343).

## Limitations

The dataset was collected from the first 200 API search results for each genre rather than through random sampling. The findings therefore should not be generalized to all books.

## Dataset

[View the published dataset on Kaggle](https://www.kaggle.com/datasets/ipekcoskunuzer/book-page-counts-romance-fantasy-and-mystery)
