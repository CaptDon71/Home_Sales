# Home Sales Analysis

## Overview
This project uses SparkSQL to analyze home sales data, focusing on key metrics and performance optimization techniques. The analysis is implemented in a Google Colab notebook that demonstrates various Spark operations including temporary views, data partitioning, and table caching.

## Getting Started

### Prerequisites
- Google account to access Google Colab
- Basic understanding of PySpark and SQL

### Setup Instructions
1. Download the `Home_Sales.ipynb` notebook from this repository
2. Visit [Google Colab](https://colab.research.google.com)
3. Choose `File` → `Upload notebook`
4. Select the downloaded `Home_Sales.ipynb` file

## Project Tasks
- Creating temporary views with SparkSQL
- Calculating key metrics about home sales data
- Partitioning data for optimization
- Caching and uncaching temporary tables
- Verifying table caching status

## Key Features
- Performance comparison between cached and uncached queries
- Data partitioning implementation

## Notes
- Make sure to run the cells in order
- Some operations may take a few moments to complete
- Remember to uncache tables when they're no longer needed

## Running the Analysis
Follow the notebook's step-by-step instructions to:
1. Load and prepare the data
2. Create temporary views
3. Execute analysis queries
4. Implement optimization techniques
5. Compare query performance