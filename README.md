# Tokyo 2020 Olympics Medals Analysis

A Data Structures and Algorithms project developed using **Python** and **Jupyter Notebook**. This project analyzes Tokyo 2020 Olympics medal data and applies different algorithmic techniques such as country classification, dense ranking, and sorting algorithms.

## About the Project

This project focuses on analyzing Olympics medal data using Python data structures and basic algorithms. The dataset contains medal information for different countries, including gold, silver, bronze, total medals, and rank by total medals.

The project reads data from a CSV file, stores the data using lists and dictionaries, classifies countries into different medal dominance categories, ranks countries using dense ranking, and sorts medal records using different sorting algorithms.

## Features

- Reads Olympics medal data from a CSV file
- Stores country medal records using Python lists and dictionaries
- Calculates gold, silver, and bronze medal percentages
- Classifies countries into medal dominance categories
- Applies dense ranking based on total medals
- Sorts countries by total medals
- Implements Bubble Sort
- Implements Selection Sort
- Implements Insertion Sort
- Compares execution time of sorting algorithms
- Displays sorted and ranked medal results

## Dataset

The project uses a CSV file named:

```text
Tokyo Medals 2020.csv
```

The dataset contains the following columns:

- Country
- Gold Medal
- Silver Medal
- Bronze Medal
- Total
- Rank By Total

## Medal Classification

Countries are classified into the following categories:

| Category | Description |
|---|---|
| Gold Dominant Category | Countries where gold medals are more than 60% of total medals |
| Silver Dominant Category | Countries where silver medals are more than 60% of total medals |
| Bronze Dominant Category | Countries where bronze medals are more than 60% of total medals |
| Balanced Category | Countries with similar gold, silver, and bronze medal percentages |
| Mixed Category | Countries that do not fit into the above categories |

## Algorithms Used

### Dense Ranking

Dense ranking is used to rank countries based on their total medals. Countries with the same total medal count receive the same rank, and the next rank continues without gaps.

### Bubble Sort

Bubble Sort is used to sort countries in descending order based on total medals by repeatedly comparing and swapping adjacent elements.

### Selection Sort

Selection Sort is used to sort countries by repeatedly selecting the country with the highest total medals and placing it in the correct position.

### Insertion Sort

Insertion Sort is used to sort countries by inserting each country into its correct position based on total medals.

## Data Structures Used

The project uses the following Python data structures:

- List
- Dictionary
- Nested dictionary
- List of dictionaries

Example structure:

```python
country_info = {
    "Country": "Japan",
    "Gold": 27,
    "Silver": 14,
    "Bronze": 17,
    "Total": 58,
    "Rank": 5
}
```

## Tech Stack

- Python
- Jupyter Notebook
- CSV module
- Time module
- Data Structures and Algorithms

## Learning Outcomes

Through this project, the following concepts are demonstrated:

- Reading data from CSV files
- Using lists and dictionaries
- Creating nested data structures
- Categorizing data based on conditions
- Calculating percentages
- Implementing dense ranking
- Implementing sorting algorithms manually
- Comparing sorting algorithm execution time
- Understanding algorithmic thinking using real-world data


## Author

**Bibek Karki**


## License

This project is created for academic and learning purposes.
