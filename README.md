# README

This repository contains code for analyzing network data from an Excel file using Python libraries like pandas, numpy, networkx, matplotlib, and seaborn. The code reads the data from the Excel file, performs data preprocessing, and then calculates various centrality measures such as degree centrality, eigenvector centrality, in-degree centrality, out-degree centrality, PageRank, and clustering coefficient. It also provides visualizations to understand the relationships between different centrality measures. Please refer to the code and comments for more details.

## Installation

To run this code, make sure you have the following dependencies installed:

- pandas
- numpy
- networkx
- matplotlib
- seaborn

You can install these dependencies using pip:

```
shell

```

```
pip install pandas numpy networkx matplotlib seaborn

```

## Usage

1. Clone this repository:

```
shell

```

```
git clone <repository_url>
cd <repository_directory>

```

1. Make sure you have the required data file (`who_talks_to_whom.xlsx`) in the same directory.
2. Run the Python code:

```
shell

```

```
python analyze_network_data.py

```

1. The code will generate various centrality measures and visualizations. The top 10 nodes for each centrality measure will be displayed in the console.
2. Explore the code and comments to understand the analysis process and modify it as needed for your own data.

## Data Preprocessing

The code performs the following data preprocessing steps:

1. Reads the data from the Excel file into a pandas DataFrame.
2. Removes any empty cells or "-" values from the data.
3. Transposes the data to have "from" as rows and "to" as columns.
4. Removes self-loops from the data (rows where "from" and "to" are the same).

## Centrality Measures

The code calculates the following centrality measures:

- Degree centrality
- Eigenvector centrality
- In-degree centrality
- Out-degree centrality
- PageRank
- Clustering coefficient
- Closeness centrality

## Visualizations

The code includes visualizations to understand the relationships between different centrality measures:

- Scatter plot of clustering coefficient vs. degree centrality
- Scatter plot of closeness centrality vs. degree centrality

Please refer to the code comments for a detailed explanation of each visualization.

## References

- [NetworkX documentation: Centrality algorithms](https://networkx.org/documentation/stable/reference/algorithms/centrality.html)
- [Understanding the concepts of Eigenvector Centrality and PageRank](https://www.strategic-planet.com/2019/07/understanding-the-concepts-of-eigenvector-centrality-and-pagerank/)

Feel free to explore the code and modify it according to your requirements.
