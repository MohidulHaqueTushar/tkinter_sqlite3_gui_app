# Tkinter GUI Application with SQLite3 Database

This is a desktop application built using **Python's Tkinter** library for the graphical user interface and **SQLite3** for data storage and retrieval. The application simulates a cryptocurrency portfolio manager with add, update, delete, and display functionalities.

The project is fully functional and also includes an [executable version](https://github.com/MohidulHaqueTushar/tkinter_sqlite3_gui_app/tree/main/dist) created with `pyinstaller` for easy distribution and use without needing Python installed.

---

## Features

- **Connect to SQLite3 Database**  
  Establishes a robust connection between the UI and an SQLite3 database for real-time interaction and data manipulation.

- **Fetch Data from Database**  
  Retrieves coin data (symbol, amount, and price) and displays it within the application interface.

- **Get Data with CoinMarketCap API**  
  Integrates real-time cryptocurrency data from [CoinMarketCap API](https://coinmarketcap.com/api/), enabling dynamic updates and market-based value calculations.

- **Modify Application Layout**  
  Improvements and adjustments made to enhance usability and aesthetics of the UI.

- **Add Coin Functionality**  
  Users can insert new cryptocurrency records into the database using an intuitive form.

- **Update/Delete Coin Records**  
  Built-in support to update existing records or delete them entirely via input fields and buttons.

- **Solve Layering Issues**  
  Addressed overlapping widget problems and ensured the interface resets correctly.

- **Notification System**  
  Integrated message box popups for confirmation and alerts (e.g., portfolio cleared).

- **Navigation System with Menu Bar**  
  Implemented a top-level navigation bar that includes options like clearing the portfolio or exiting the app.

---

## Technologies Used

- **Python 3**
- **Tkinter**
- **SQLite3**
- **CoinMarketCap API**
- **PyInstaller** (for executable generation)

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/https://github.com/MohidulHaqueTushar/tkinter_sqlite3_gui_app.git
```
