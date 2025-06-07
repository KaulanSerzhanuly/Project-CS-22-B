# 🛍️ Amazon Review Collector

This project is a Python-based web scraping tool built with BeautifulSoup and `requests` that collects and displays product reviews from Amazon product pages. It is implemented in a Jupyter Notebook for easy visualization and testing.

## 📌 Features

- Takes an Amazon product URL as input.
- Extracts the product title.
- Scrapes review titles and review texts.
- Displays the reviews in a structured format.

## 📂 Project Structure

```
📦 Amazon Review Collector
├── Copy_of_Amazon_review_collector (1).ipynb
└── README.md
```

## 🧰 Requirements

- Python 3.7+
- Jupyter Notebook
- `requests`
- `bs4` (BeautifulSoup)
- `html5lib`

### Installation

To set up the environment, install the required packages:

```bash
pip install requests beautifulsoup4 html5lib
```

Or you can install all dependencies using:

```bash
pip install -r requirements.txt
```

## 🚀 How to Use

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `Copy_of_Amazon_review_collector (1).ipynb`.

3. Enter the URL of an Amazon product (make sure it's a public and accessible URL with reviews).

4. Run the cells to scrape and display reviews.

> ⚠️ **Note:** This project is intended for educational purposes only. Frequent or automated scraping of Amazon may violate their Terms of Service.

## 📎 Example Output

The notebook will display:
- The product name.
- The review titles and review contents.
  
Example:
```
Product Title: XYZ Bluetooth Headphones

Review 1 Title: Great Sound!
Review 1 Text: These headphones have amazing sound quality...

Review 2 Title: Worth the Price
Review 2 Text: For the price, the features are amazing...
```

## 🛑 Disclaimer

This script is intended solely for personal or educational use. Web scraping should be done responsibly and in accordance with the website’s terms and conditions.

## 📫 Contact

For questions or contributions, feel free to open an issue or submit a pull request.
