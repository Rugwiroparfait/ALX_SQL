# ALX SQL Data Science Exercises

Welcome to my SQL exercise repository for the ALX Data Science Program! This repository contains a collection of Jupyter notebooks that demonstrate various SQL concepts and techniques learned throughout the program.

## 📚 Repository Overview

This repository contains hands-on SQL exercises and tutorials covering fundamental to advanced SQL concepts. All exercises are implemented using Jupyter notebooks with SQL magic commands, allowing for an interactive learning experience.

## 🎯 Learning Objectives

Through these exercises, I have learned to:
- Write basic SQL queries using `SELECT`, `WHERE`, and `LIMIT` statements
- Perform data filtering and analysis using logical and comparison operators
- Use SQL functions for string manipulation, numeric calculations, and date/time operations
- Apply aggregation functions and window functions for advanced data analysis
- Join multiple tables and work with relational databases
- Create summary statistics and reports
- Clean and transform data using SQL

## 📁 Repository Structure

### Basic SQL Operations
- `Basic SQL queries in a notebook 1 [Exercise].ipynb` - Fundamental SELECT, WHERE, and LIMIT operations
- `SELECT and WHERE [Notebook].ipynb` - Basic querying techniques
- `interacting_with_sql.ipynb` - Introduction to SQL in Jupyter notebooks
- `sql_notebooks.ipynb` - General SQL notebook practices

### Data Types and Functions
- `Converting between data types.ipynb` - Type conversion and casting
- `SQL string functions.ipynb` - String manipulation functions
- `Using SQL string functions to clean data.ipynb` - Data cleaning with string functions
- `SQL numeric functions and aggregations [Exercise].ipynb` - Mathematical operations and aggregations
- `Transform columns using numeric functions[Notebook].ipynb` - Column transformations
- `Initial data analysis with numeric functions [Notebook].ipynb` - Exploratory data analysis
- `SQL DateTime functions [Exercise].ipynb` - Date and time operations
- `Quick_maths.ipynb` - Mathematical calculations in SQL

### Logical Operations and Filtering
- `Logical and comparison operators ii.ipynb` - Advanced logical operations
- `Using logical and comparison operators [Notebook].ipynb` - Filtering data with conditions
- `Conditional-calculations-using-IF.ipynb` - Conditional logic in SQL
- `Grouping with a case statement.ipynb` - CASE statements for data categorization

### Advanced SQL Techniques
- `SQL window functions [Exercise].ipynb` - Window function basics
- `Aggregation using window functions [Notebook].ipynb` - Advanced aggregations
- `Using value based window functions [Notebook].ipynb` - Value-based window operations
- `Top-N analysis using ranking window functions [Notebook].ipynb` - Ranking and top-N analysis

### Data Analysis and Reporting
- `Create a summary statistic report in SQL [Notebook].ipynb` - Statistical reporting
- `Filtering and analysing summary statistic report [Notebook].ipynb` - Report analysis
- `Reading data across multiple tables [Notebook].ipynb` - Multi-table operations

### Documentation and Best Practices
- `Aliasing and commenting in SQL.ipynb` - Code documentation and readability

## 🛠️ Technologies Used

- **Database**: SQLite (Chinook sample database)
- **Environment**: Jupyter Notebook
- **Language**: SQL with Python integration
- **Tools**: SQL magic commands (`%%sql`, `%sql`)

## 🗃️ Database Schema

Most exercises use the Chinook database, which represents a digital media store with the following main tables:
- `customers` - Customer information
- `employees` - Employee data
- `invoices` - Sales transactions
- `invoice_items` - Individual items in transactions
- `tracks` - Music tracks
- `albums` - Music albums
- `artists` - Music artists
- `genres` - Music genres
- `media_types` - File formats
- `playlists` - Music playlists

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- SQLite
- Required Python packages:
  ```bash
  pip install jupyter
  pip install ipython-sql
  pip install sqlalchemy
  ```

### Running the Notebooks
1. Clone this repository:
   ```bash
   git clone https://github.com/Rugwiroparfait/ALX_SQL.git
   cd ALX_SQL
   ```

2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open any notebook file (`.ipynb`) and run the cells sequentially

4. Load the SQL extension in each notebook:
   ```python
   %load_ext sql
   %sql sqlite:///chinook.db
   ```

## 📖 Key Concepts Covered

### Beginner Level
- Basic SELECT statements
- WHERE clauses and filtering
- LIMIT and data sampling
- Comparison and logical operators

### Intermediate Level
- JOIN operations
- Aggregate functions (COUNT, SUM, AVG, etc.)
- GROUP BY and HAVING clauses
- String and numeric functions
- Date/time manipulations

### Advanced Level
- Window functions (ROW_NUMBER, RANK, DENSE_RANK)
- Common Table Expressions (CTEs)
- Complex subqueries
- Data analysis and reporting techniques

## 🎓 About ALX Data Science Program

This repository is part of my coursework in the ALX Data Science Program, a comprehensive program designed to build practical skills in data science, including:
- Data manipulation and analysis
- Statistical analysis
- Machine learning
- Data visualization
- Database management

## 📝 License

This project is for educational purposes as part of the ALX Data Science Program.

## 🤝 Contributing

These are personal exercise solutions, but feel free to:
- Report issues or suggest improvements
- Share alternative solutions
- Provide feedback on code quality

## 📧 Contact

For questions or discussions about these SQL exercises, feel free to reach out!

---

*Happy Learning! 🚀*

**Note**: This repository demonstrates my progress and understanding of SQL concepts throughout the ALX Data Science Program. Each notebook represents a step in my learning journey.
