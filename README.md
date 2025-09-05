# Personal Finance Management System  

A simple **command-line Python application** to track income, expenses, and savings using CSV storage and data visualization. Users can add new transactions, view reports within a date range, and generate income/expense graphs for better financial insights.  

---

## Features  

- **Add Transactions**  
  - Record income or expenses with date, amount, category, and description.  
  - Transactions are saved in a CSV file for persistence.  

- **View Transactions**  
  - Filter and display transactions within a given date range.  
  - Provides a summary of total income, expenses, and net savings.  

- **Visualize Data**  
  - Plot daily income and expenses as a line chart using Matplotlib.  

- **Simple CLI Interface**  
  - Menu-driven system for adding, viewing, and analyzing finances.  

---

## Technologies Used  

- **Python 3.8+**  
- [Pandas](https://pandas.pydata.org/) – Data handling and CSV operations.  
- [Matplotlib](https://matplotlib.org/) – Plotting and visualization.  
- **CSV** – Transaction storage.  

---

## Project Structure  

```bash
├── finance_data.csv        # CSV file storing transactions (auto-created)
├── main.py                 # Main script (menu and program logic)
├── data_entry.py           # Handles user input validation (date, amount, category, description)
```

## Installation

### Clone the repository:
```bash
git clone https://github.com/Tewodros-Berhane/Personal-Finance-Tracker.git
cd personal-finance-manager
```

### Install dependencies:
```bash
pip install pandas matplotlib
```

### Run the program:
```bash
python main.py
```
