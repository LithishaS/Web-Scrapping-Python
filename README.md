# 🌐 Web Scraping using BeautifulSoup

A Python web scraping project that extracts information about the largest companies in the United States from Wikipedia and stores the data in a CSV file.

---

## 📌 Project Overview

This project demonstrates how to scrape structured data from a webpage using the Requests and BeautifulSoup libraries. The extracted HTML table is converted into a Pandas DataFrame and exported as a CSV file.

---

## ✨ Features

- Sends HTTP requests to a webpage
- Parses HTML using BeautifulSoup
- Extracts tabular data
- Converts data into a Pandas DataFrame
- Exports scraped data to CSV

---

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup4
- Pandas
- Jupyter Notebook

---

## 📂 Project Structure

```text
web-scraping-python/

│── Web scraping.ipynb
│── scraping.py
│── Companies.csv
│── README.md
│── requirements.txt
│── .gitignore
```

---

## 🌍 Website Scraped

Wikipedia

**Page:**

Largest companies in the United States by revenue

---

## ⚙️ Workflow

1. Send an HTTP request to the webpage.
2. Parse the HTML content using BeautifulSoup.
3. Locate the required HTML table.
4. Extract table headers and rows.
5. Store the data in a Pandas DataFrame.
6. Export the data to `Companies.csv`.

---

## 📄 Output

The extracted data contains information about major U.S. companies, including:

- Company Name
- Industry
- Revenue
- Employees
- Headquarters
- Other available table columns

The data is saved as:

```
Companies.csv
```

---

## 🚀 How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Run all cells to generate the CSV file.

---

## 🔮 Future Improvements

- Scrape multiple web pages
- Handle pagination
- Add exception handling
- Save data into a SQL database
- Build an automated web scraper

---

## 👩‍💻 Author

**Lithisha S**
