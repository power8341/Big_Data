# Jupyter Notebook: TP_3_1_MySQL_PY

## Overview
This Jupyter Notebook (`TP_3_1_MySQL_PY.ipynb`) demonstrates how to interact with MySQL using Python. It covers various aspects of database operations such as connecting to MySQL, executing queries, retrieving data, and performing CRUD operations.

## Prerequisites
Before running the notebook, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook or JupyterLab
- MySQL Server
- Required Python libraries:
  - `mysql-connector-python`
  - `pandas`

### Install Dependencies
To install the required packages, run:
```bash
pip install mysql-connector-python pandas
```

## Usage
1. **Clone the Repository** (if using GitHub)
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. Open `TP_3_1_MySQL_PY.ipynb` in Jupyter Notebook and follow the instructions within the notebook.

## Key Features
- **Database Connection:** Establishes a connection to MySQL using `mysql.connector`.
- **Executing Queries:** Runs SQL queries directly from Python.
- **Fetching Data:** Retrieves and displays data using Pandas DataFrames.
- **Insert, Update, Delete:** Performs CRUD operations on MySQL tables.
- **Error Handling:** Includes exception handling for database operations.

## Configuration
Modify the database connection details in the notebook:
```python
config = {
    'user': 'your_username',
    'password': 'your_password',
    'host': 'your_host',
    'database': 'your_database'
}
```
Replace `your_username`, `your_password`, `your_host`, and `your_database` with your actual database credentials.

