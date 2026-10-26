Netflix Movies and TV Shows – A Content Journey of 10 Years

1. Problem Statement & Research Question
Research Question: What has been the change in the percentage of movies vs. TV shows that Netflix released in the last decade? Do certain genres rule particular release years?
Reasons for choosing the research problem: The knowledge about streaming platform content strategies can be very useful in understanding the approaches to entertainment production and scaling.

2. Data Source and License
3. Data source: Netflix Movies and TV Shows Dataset at Kaggle (scraped from Flixable).
License: CC0: Public Domain.

3. Data Cleaning Log
Initial size of the dataset verified (8,807 entries).
Duplicate rows checked (no duplicates found).
Essential columns verified (type, release_year, title, listed_in).
Comma-separated multi-genre entries were split and exploded into the dataset for precise genre analysis.

4. Important Insights & Visualizations
Insight 1 (Movie vs. TV Show Shift): Netflix saw exponential growth in its movies from 2015-2018 (760+ per year) after which there was a shift towards more diverse TV shows.
Insight 2 (Dominated Genres): International Movies (2,752 titles) and Dramas (2,427 titles) dominate Netflix’s overall catalog, with Comedies following.
Insight 3 (Change in Genre Composition Over Time): Titles belonging to the leading genres (International Movies, Dramas, and Comedies) rapidly increased from 2015-2018, after which there was a slow decline until 2021.

5. Limitations
The data is only available till the end of 2021; hence, the current changes in content strategy will not be included.
Genre categories are user-defined tags and could belong to different genres simultaneously.

6. How to Run
1. Fork or clone the repository cs82a-portfolio.
2. Go into the folder named final_project.
3. Make sure pandas, matplotlib and seaborn libraries are installed.
4. Open and run netflix_analysis.ipynb file using Jupyter Notebook.

Prompt Disclosure
Data License: CC0 Public Domain (scraped from Flixable via Kaggle).
PII Handling: The dataset contains public content metadata only; no personal identifiable information (PII) is present.
AI Assistance: Was used as a learning assistant to assist with code debugging (fixing Seaborn deprecation warnings), refining dataset cleanup logic, and structuring the project report/README format.
