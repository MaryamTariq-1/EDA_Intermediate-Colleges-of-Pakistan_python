# Exploratory Data Analysis on Intermediate Colleges in Pakistan

## Introduction
This project is part of my internship at CodexCue, focusing on exploratory data analysis (EDA) of intermediate colleges in Pakistan. The aim is to analyze and visualize various aspects of the dataset, providing actionable insights.

## Dataset
The dataset contains information about intermediate colleges in Pakistan, including attributes such as location, sector, affiliation, rating, and study programs.
'All the Intermediate Colleges in Pakistan.csv'

## Steps and Methodologies

1. **Data Cleaning:**
    - Handled missing values for 'Location', 'Sector', and 'Affiliation'.
    - Converted 'Rating' to numerical values.

2. **Data Transformation:**
    - Extracted city names from college names.
    - Derived regions based on city names.

3. **Analysis:**
    - **Regional Analysis:** Assessed college distribution and average ratings across different regions.
    - **Sector Analysis:** Investigated distribution and ratings of public and private sector colleges.
    - **Affiliation Insights:** Analyzed college affiliations' impact on educational quality.
    - **Program Analysis:** Explored the diversity and popularity of study programs.

## Visualizations
1. **Distribution of Ratings:**
    - Histogram showing the frequency distribution of ratings.

2. **Count of Institutions by Sector:**
    - Count plot displaying the number of institutions in public and private sectors.

3. **Count of Institutions by Affiliation:**
    - Count plot of institutions categorized by their affiliations.

4. **Count of Institutions by Top 20 Locations:**
    - Count plot of institutions in the top 20 locations.

5. **Distribution of Study Programs:**
    - Count plot of the top 20 study programs offered by these institutions.

6. **Box Plot of Ratings:**
    - Box plots comparing ratings across sectors, affiliations, and locations.

7. **Correlation Analysis:**
    - Heatmap of the correlation matrix for numerical variables.
    - Cramér's V correlation heatmap for categorical variables.

## Results
- Identified regional and sector-specific trends.
- Highlighted the impact of affiliations on ratings.
- Provided insights into the popularity and diversity of study programs.

## Conclusion
This analysis provides valuable insights aimed at bridging educational gaps and enhancing the quality of education in Pakistan.

## Future Work
- Extend the analysis to other educational datasets.
- Implement predictive models to forecast trends.

## How to Run
1. Clone the repository:
    ```sh
    git clone https://github.com/MaryamTariq-1/EDA_Intermediate-Colleges-of-Pakistan_python.git
    ```
2. Navigate to the project directory:
    ```sh
    cd eda-intermediate-colleges-pakistan
    ```
3. Install the required libraries:
    ```sh
    pip install numpy
    pip install pandas
    pip install matplotlib
    pip install seaborn
    pip install scipy
    ```
4. Run the analysis:
    ```sh
    All the Intermediate Colleges in Pakistan.ipynb
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- CodexCue for the internship opportunity.
- Mentors and colleagues for their support and guidance.
