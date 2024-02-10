# Cinema Success Insights

-------------------------------------------

## Description

This is a project that studies the success of movies from a group of datasets. The reason of this project is to finish the second phase of the FlatIron Data Science bootcamp. It was required to carry out an investigation of zippedData containing datasets to come up with 3 business recommendations for investments that the head of a company's new movie studio can use to help decide what type of films to create.

*Your company now sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of your company's new movie studio can use to help decide what type of films to create.*

In order to arrive to solid business recommendations for our new film studio's production strategy we belive it's important to answer the three following questions:

- 1. First Question: Which movie genre yields the highest ROI?
- 2. Second Question: What is the relationship between a movie's run-time and its ROI and production costs?
- 3. Third Question: How does a director's involvement correlate with a movie's ROI and production costs?

## Methodology

These are steps followed in order to perform the aircraft analysis:
- 1. Descriptive Statistics
- 2. First Question
- 3. Second Question
- 4. Third Question
- 5. Results

## Sources

The dataset is comprised in a zippedData folder that contains datasets from:
- Box Office Mojo
- IMDB
- Rotten Tomatoes
- TheMovieDB
- The Numbers

Some of the datasets are CSV, others are TSV and IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-2-project-v3/main/movie_data_erd.jpeg)


## Conclusion

After a comprehensive analysis of the different datasets, our research has culminated in targeted recommendations for the company's strategic entry investment in the cinema market. The key findings of our study have highlighted the importance of investing in movies and cinematic traits with a proven high percentage of ROI especially.

Our three primary recommendations are as follows:

1. First business recommendation: Invest in horror movies. 

2. Second business recommendation: Prioritize investment in short films (that have a running time of less than 90 minutes).

3. Third business recommendation: Focus investments on movies that have been directed by: Sujit Mondal.

Please find bellow a more detailed description of them:

1. Invest in horror movies: Data shows that they have more than a 750% on ROI.

![Business Recommendation 1](/visualizations/Business_Recommendation_1.png)

2. Invest in short films: Movies that have a run_time less than 90 minutes have the highest ROI_% and the shortest production budgets.

![Business Recommendation 2](/visualizations/Business_Recommendation_2.png)

3. We would recommend to hire Sujit Mondal as one of the directors. He has directed 7 films, has a ROI of about 25000% and the production budget of the movies he did are almost negligeable. 

![Business Recommendation 3](/visualizations/Business_Recommendation_3.png)

These recommendations aim to provide the board of the company with a data-driven foundation for making informed decisions before deciding which films to create.

## Author

My name is Miguel Barriola Arranz. I am an Industrial Engineer and a Duke graduate student in Engineering Management. 
I am currently working in the microchip industry and further expanding my skillset in data science. 

- LinkedIn: https://www.linkedin.com/in/miguel-barriola-arranz/

## Presentation

Please find here the link to the project presentation: 
- Tableau: https://public.tableau.com/app/profile/miguel.barriola.arranz/viz/Aircraft_Safety_Analysis_Representation/Dashboard1?publish=yes

## Technologies

I have used **Python** with Jupyter notebook and I have also used **Tableau** to represent the business insight results.

## Project Status

The project is in a development process at this moment. 

## What to find in the repository

There is a folder called notebook that contains all the necessary analysis.

There is a requirements.txt that contains the information of the libraries used in this project.

There is a .gitignore that allows to exclude files that are of no interest.

There is a results_data folder that contains the filtered dataset from all the analysis. This final dataset is used in Tableau to carry out results representations. 

There is a branch named feature/phase1 to work in the project and I have done a pull request to **develop**. This is the branch that contains all the updated information.
