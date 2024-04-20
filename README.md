# From Canvas to Database: Leveraging Artist Data to Drive Art Business Strategies

This project utilizes a dataset of the 50 most influential artists of all time to explore various artistic trends and their implications for art business strategies. The data includes details about the artists' genres, nationalities, and the total number of paintings they produced, sourced from a collection on Kaggle.

## Motivation

This initiative was driven by a personal curiosity about the relationships between artists' genres, their nationalities, and their productivity over time. By delving into these aspects, the project seeks to offer insights that could assist art galleries, auction houses, and museums in planning exhibitions and understanding trends in the art market.

## Files in the Repository

- **Best_Artists_Ana.ipynb**: Jupyter notebook containing all data analysis processes, from data cleaning and exploration to detailed statistical analysis and visualizations.
- **artists.csv**: The dataset file used for this analysis.
- **README.md**: This file, explaining the project, its structure, and how to navigate the repository.

## Libraries Used

The analysis leverages several Python libraries:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For high-level interface for drawing attractive and informative statistical graphics.
- **SciPy**: For performing the chi-square test of independence.

## Analysis Summary

The analysis focuses on three main aspects:

- **Genre Distribution**: Identification of the most common genres among the artists and how this correlates with the volume of paintings produced.
- **Nationality and Genre Correlation**: Investigation into whether there is a correlation between the artists' nationalities and the genres they are associated with.
- **Artist Productivity Over Time**: Examination of trends in the productivity of artists over the years.

## Results

- **Genre Distribution**: Impressionism and Post-Impressionism are identified as the most prevalent genres.
- **Nationality and Genre Correlation**: Significant correlations were found between nationalities and preferred genres, particularly among French artists with Impressionism.
- **Artist Productivity Over Time**: There was a noticeable fluctuation in productivity, with peaks in certain decades likely influenced by historical events and artistic movements.

## How to Run

To run the notebook:

1. Ensure you have Python installed on your system.
2. Install the necessary libraries using pip:
   ```bash
   pip install pandas matplotlib seaborn scipy numpy
3. Open the Jupyter Notebook in your environment and run each cell sequentially.
## Acknowledgements
The dataset used in this project was obtained from Kaggle, compiled by Ikarus777, who sourced it from Wikipedia. The motivation for this analysis was inspired by personal interests and discussions on art trends.
