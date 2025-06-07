# 🛍️ Amazon Review Collector (Google Colab)

This project is a Python-based web scraping tool built with `requests` and `BeautifulSoup` to collect product reviews from Amazon product pages. It is implemented and intended to be run on **Google Colab**, which makes it easy to use without any local setup.

## 📌 Features

- Accepts an Amazon product URL as input.
- Scrapes product title, review titles, and review content.
- Outputs the reviews in a readable format within Colab.

## 📂 Project Files

```
📦 Amazon Review Collector
├── Copy_of_Amazon_review_collector
└── README.md
```

## 🧰 Requirements

All dependencies can be installed directly inside the Colab notebook using:

```python
!pip install requests beautifulsoup4 html5lib
```

These libraries are typically already available in Colab by default.

## 🚀 How to Use

1. Open the notebook on Google Colab.

2. Install dependencies (if needed) using:
   ```python
   !pip install requests beautifulsoup4 html5lib
   ```

3. Enter the URL of an Amazon product (with reviews) when prompted.

4. Run all cells to view:
   - The product name.
   - Review titles.
   - Review texts.

> ⚠️ **Important:** This tool is for educational use only. Scraping Amazon frequently or at scale may violate their Terms of Service.
thats why we used already existing data.
## 📎 Sample Output

```
Product Title: Example Headphones

Review 1 Title: Great Sound!
Review 1 Text: These headphones sound amazing...

Review 2 Title: Worth the Price
Review 2 Text: For the price, these are unbeatable...
```

## 🛑 Disclaimer

This script is intended for learning and personal use only. Be mindful of the terms and policies of the websites you interact with.
