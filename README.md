# Jedi Archive Data

This project aims to centralize and organize a significant amount of data related to the **Star Wars** universe. The data is structured into DataFrames (CSV/JSON), categorized according to each work in the franchise, including movies, books, animations, games, and series.

## 🚀 Project Objective

To create a robust data repository for enthusiasts, developers, and data analysts who want to explore the connections, characters, planets, and events of a galaxy far, far away.

## 🛠️ Extraction Methodology (ETL)

Data collection is being carried out through:
*   **Public APIs:** Consumption of open databases about Star Wars.
*   **Web Scraping:** Extracting data from web pages using:
    *   `Python`
    *   `Beautiful Soup`
    *   `Requests`
    *   `Pandas` (for dataframe manipulation and structuring)

> **Note:** The complete source code of the extraction scripts and the ETL (Extract, Transform, Load) process will be published later in a separate repository.

## 📂 Data Structure

The data is organized by work. Currently, the project includes:

*   **Clone Wars:**
    *   `cw_characters_raw.csv`: Raw list of characters.
    *   `cw_characters_force_users.csv`: Refined filter of Force users (Jedi, Sith, Nightsisters, etc.).

## ⚖️ License and Usage

This project is intended for educational and research purposes. All rights to the Star Wars brand belong to Disney/Lucasfilm.

---
*May the Force be with you.*
