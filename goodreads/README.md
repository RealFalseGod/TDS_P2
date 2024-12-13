# Data Analysis Report

### Detailed Narrative of Data Analysis Results for 'goodreads.csv'

#### Overview
The dataset 'goodreads.csv' comprises information on 10,000 distinct books available on Goodreads. The dataset includes key attributes such as book IDs, authors, publication details, ratings, and more. In our analysis, we identified several insights regarding trends, outliers, correlations, and anomalies across different attributes.

#### Data Composition
- **Books Count**: The dataset consists of 10,000 entries, covering various attributes. Notably, the authors are represented with a wide variety, leading to a richness in Literature.
- **Authors**: A total of 4,664 unique authors are found in the data, with Stephen King being the most frequently mentioned author, appearing 60 times.
  
#### Publication Trends
- **Original Publication Year**: The books in this dataset were originally published from as early as the year -1750 to as recently as 2017, with a mean publication year of approximately 1982. This range highlights the extensive history of literature covered by the dataset.
- **Books Count**: The mean number of books associated with each entry is approximately 76, indicating that many authors have a significant number of published works, with one author having a maximum of 3,455 books.

#### Rating Analysis
- **Average Rating**: The average rating across all books is around 4.00, with a standard deviation of 0.25, suggesting that most books received favorable reviews. The ratings range from the minimum of 2.47 to a maximum of 4.82.
- **Ratings Distribution**: 
  - The distribution of ratings (1-5) shows significant skewness. The count of ratings received follows a pattern where higher ratings are more common:
    - Average ratings of 1, 2, 3, 4, and 5 are approximately 1,345, 3,111, 11,476, 19,966, and 23,790 respectively. This suggests that lower ratings are given less frequently than higher ratings.

#### Insights from Correlation Analysis
- **Ratings Correlation**: 
  - Strong positive correlations exist among the different ratings categories (e.g., `ratings_count`, `work_ratings_count`, and individual ratings from 1-5), indicating that books with high engagement receive positive reviews regardless of the specific rating level.
  - Negative correlations between `books_count` and various ratings attributes suggest that books with more extensive works recorded often receive lower ratings, potentially indicating that prolific authors may have varying quality in their works.
- **Work Text Reviews Count**: The correlation between `work_text_reviews_count` and ratings demonstrates that books which receive a significant amount of textual reviews tend to achieve higher ratings. This could imply that readers often reward books with more detailed feedback.

#### Missing Values
- A notable number of missing values, particularly in `isbn` (700 missing), `isbn13` (585 missing), `original_title` (585 missing), and `language_code` (1,084 missing), indicates potential data quality issues. This aspect deserves attention, as it may limit some analysis, especially when conducting searches based on these attributes.

#### Outliers and Anomalies
- **High Ratings Count**: The maximum value for `ratings_count` (4,780,653) indicates a potential outlier, likely representing a highly popular book. A similar situation occurs for `work_ratings_count` and `work_text_reviews_count`, which also show extreme values (4,942,365 and 155,254 respectively) showcasing that certain books receive inordinate amounts of attention.
- **Low Ratings**: There are also books with notably low average ratings (minimum being 2.47), indicating that not all works enjoy a good reception; pinpointing these books can help in understanding the elements leading to poor ratings.

#### Language Trends
- The dataset supports 25 unique language codes, with English (`eng`) being the most represented, appearing 6,341 times, which is to be expected on a major English-language book review site. 

### Conclusion
This analysis demonstrates a rich landscape of literary information in 'goodreads.csv', revealing trends in author popularity, publication years, and ratings behavior. The correlations highlight that engagement metrics such as ratings often coexist positively, while challenges associated with extensive authorship need closer inspection. The presence of missing values hints at areas in which the dataset may be improved for future analyses.
The results can guide stakeholders interested in reader preferences, potential market trends, and quality assessments in literature. Further investigation might focus on patterns among lower-rated books and the efficacy of promotional strategies surrounding highly-rated works.

## Visualizations

![average_rating_distribution.png](average_rating_distribution.png)
![best_book_id_distribution.png](best_book_id_distribution.png)
![books_count_distribution.png](books_count_distribution.png)
![book_id_distribution.png](book_id_distribution.png)
![correlation_heatmap.png](correlation_heatmap.png)
![goodreads_book_id_distribution.png](goodreads_book_id_distribution.png)
![isbn13_distribution.png](isbn13_distribution.png)
![original_publication_year_distribution.png](original_publication_year_distribution.png)
![ratings_1_distribution.png](ratings_1_distribution.png)
![ratings_2_distribution.png](ratings_2_distribution.png)
![ratings_3_distribution.png](ratings_3_distribution.png)
![ratings_4_distribution.png](ratings_4_distribution.png)
![ratings_5_distribution.png](ratings_5_distribution.png)
![ratings_count_distribution.png](ratings_count_distribution.png)
![work_id_distribution.png](work_id_distribution.png)
![work_ratings_count_distribution.png](work_ratings_count_distribution.png)
![work_text_reviews_count_distribution.png](work_text_reviews_count_distribution.png)