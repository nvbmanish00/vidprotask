## Setup

1. Install dependencies:
   pip install -r requirements.txt

2. Ensure database.db is in project folder.

## Run SQL solution
python sql_solution.py

## Run Pandas solution
python pandas_solution.py

## Output
Both scripts generate CSV files with format:

Customer;Age;Item;Quantity

## Assumptions
- NULL quantity means item not purchased.
- Customers filtered between age 18–35.
- Only items with total quantity > 0 included.