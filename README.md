# IMDB-Big-Data-Analysis-Using-PySpark-on-AWS-EMR

This project demonstrates distributed data analysis on IMDB datasets using Apache Spark on AWS EMR. Data was read from public AWS S3 buckets and analyzed using PySpark in a Jupyter Notebook environment. Key insights include top movie genres, job categories, and actor-based movie filtering.

# Tools & Technologies:

- AWS EMR (Elastic MapReduce)
- PySpark (DataFrames & Spark SQL)
- Jupyter Notebook on EMR
- AWS S3 (data storage)
- Matplotlib (visualizations)

# Data Sources:

- actors.csv: Contains information about actors, including their primary name, birth year, and filmography.
- genres.csv: Links movies to their corresponding genres and release years.
- movie_actors.csv: Connects actors to the movies they have participated in, specifying their roles and job titles.
- movie_ratings.csv: Stores average ratings and vote counts for each movie.

# Methodology:

- Load the data into Spark SQL DataFrames.
- Perform data cleaning and pre-processing as necessary.
- Join the DataFrames based on common identifiers (e.g., tconst) to combine information.
- Utilize Spark SQL functions and Python libraries (e.g., pandas) for data manipulation and analysis.
- Calculate descriptive statistics, perform aggregations, and apply data visualization techniques to present findings.

# Artifacts:

- Project2_Analysis.ipynb: Jupyter Notebook with code and output
- Project2_Analysis.html: Exported notebook in HTML
- assets/: Screenshots of EMR and notebook configuration
- README.md: Project overview and setup instructions
