# scrapscraper
A fast and lightweight Python web scraping package.

---

## 📦 About
`scrapscraper` is a Python package designed for simple and efficient web scraping,  
with both CLI and library support.

---

## Installation
To install `scrapscraper` simply use pip:

```bash
pip install scrapscraper
Or clone the repo: git clone https://github.com/skelliyB/scrapscraper
```

## Functions

🧩 Functions
Added in v2.1.0
```python
scraper()
Basic usage example:


from scrapscraper import scraper

url = "https://example.com"
data = scraper(url, timeout=10)

print(data)
scrapedepth()
Basic usage example:


from scrapscraper import scrapedepth

print(scrapedepth("https://example.com", timeout=10, prettyprint=True, depth=1, headers=None))
scrapelinks()
Basic usage example:


from scrapscraper import scrapelinks

links = scrapelinks("https://example.com", timeout=10, headers=None)
print(links)
scrapemeta()
Basic usage example:


from scrapscraper import scrapemeta

meta = scrapemeta("https://example.com", timeout=10, headers=None)
print(meta)
scrapetitle()
Basic usage example:


from scrapscraper import scrapetitle

title = scrapetitle("https://example.com", timeout=10, headers=None)
print(title)
scrapetext()
Basic usage example:


from scrapscraper import scrapetext

text = scrapetext("https://example.com", timeout=10, headers=None)
print(text)
