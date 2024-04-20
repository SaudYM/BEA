From Canvas to Database: Leveraging Artist Data to Drive Art Business Strategies
This project uses a dataset of the 50 most influential artists of all time to explore various artistic trends and their implications for art business strategies. The dataset includes information about the artists' genres, nationalities, and the number of paintings they produced, sourced from a collection on Kaggle.

Motivation
The motivation behind this project stemmed from personal curiosity about the relationships between artists' genres, their nationalities, and their productivity over time. By analyzing these aspects, the project aims to provide insights that could help art galleries, auction houses, and museums in planning exhibitions and understanding art trends.

Files in the Repository
Best_Artists_Ana.ipynb: Jupyter notebook containing all the data analysis processes, from data cleaning and exploration to detailed statistical analysis and visualizations.
artists.csv: The dataset file used for this analysis.
README.md: This file, explaining the project, its structure, and how to navigate the repository.
Libraries Used
The project uses several Python libraries:

Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib: For creating static, interactive, and animated visualizations.
Seaborn: For high-level interface for drawing attractive and informative statistical graphics.
SciPy: For performing the chi-square test of independence.
Analysis Summary
The analysis covers three main aspects:

Genre Distribution: Identification of the most common genres among the artists and how this relates to the volume of paintings produced.
Nationality and Genre Correlation: Investigation into whether there is a correlation between the artists' nationalities and the genres they are associated with.
Artist Productivity Over Time: Examination of trends in the productivity of artists over the years.
Results
Genre Distribution: Impressionism and Post-Impressionism are the most prevalent genres.
Nationality and Genre Correlation: Significant correlations were found between nationalities and preferred genres, especially among French artists with Impressionism.
Artist Productivity Over Time: A noticeable fluctuation in productivity was observed, with peaks in certain decades likely influenced by historical events and artistic movements.
How to Run
To run the notebook:

Ensure you have Python installed on your system.
Install the necessary libraries using pip:
Copy code
pip install pandas matplotlib seaborn scipy numpy
Open the Jupyter Notebook in your environment and run each cell sequentially.
Acknowledgements
The dataset used in this project was obtained from Kaggle, compiled by Ikarus777, who collected it from Wikipedia. The motivation for this analysis was inspired by personal interests and discussions on art trends.
