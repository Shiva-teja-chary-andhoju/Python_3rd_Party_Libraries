# 🐍 Python 3rd Party Libraries — Hands-On Notebooks

> *There are thousands of third-party Python libraries. This module covers the ones that show up in almost every real-world data project — time zones, messy date parsing, JSON, and REST APIs — with runnable Jupyter notebooks and concise, technically precise notes.*

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Actively%20Learning-brightgreen)

---

## 📚 What's Inside

| # | Notebook | Library / Topic | What you'll learn |
|---|----------|-----------------|-------------------|
| 00 | [`00_3rd_Party_Libraries.ipynb`](https://github.com/Shiva-teja-chary-andhoju/Python_3rd_Party_Libraries/blob/main/00_3rd_Party_Libraries.ipynb) | 🧭 Overview & setup | Landscape of key libraries (`pytz`, `dateutil`, `requests`, `numpy`, `pandas`, `matplotlib`), `pip install`, and virtual environments (Linux vs Windows) |
| 01 | [`01_The_pytz_Library.ipynb`](https://github.com/Shiva-teja-chary-andhoju/Python_3rd_Party_Libraries/blob/main/01_The%20pytz%20Library.ipynb) | 🌍 `pytz` | Named time zones via the IANA/Olson database, DST handling, `localize()` vs `astimezone()`, `fromutc()` |
| 02 | [`02_The_dateutil_Library.ipynb`](https://github.com/Shiva-teja-chary-andhoju/Python_3rd_Party_Libraries/blob/main/02_The%20dateutil%20Library.ipynb) | 🧠 `dateutil` | Format-free date parsing with `parser.parse`, `dayfirst` ambiguity, fuzzy parsing, `ParserError` handling |
| 03 | [`03_JSON_Data.ipynb`](https://github.com/Shiva-teja-chary-andhoju/Python_3rd_Party_Libraries/blob/main/03_JSON%20Data.ipynb) | 🧾 `json` | JSON structure, serialization (`dumps`) and deserialization (`loads`), Python ↔ JSON type mapping, non-serializable types |
| 04 | [`04_REST_APIs.ipynb`](https://github.com/Shiva-teja-chary-andhoju/Python_3rd_Party_Libraries/blob/main/04_REST%20APIs.ipynb) | 🔌 REST APIs | HTTP anatomy (URL, verbs, query args), GET/POST, authentication, data formats, status codes, hands-on with the Finnhub Stock API |
| 05 | [`05_The_requests_Library.ipynb`](https://github.com/Shiva-teja-chary-andhoju/Python_3rd_Party_Libraries/blob/main/04_REST%20APIs.ipynb) | 🌐 `requests` | HTTP for Humans: `get`/`post`/`put`, `params`, `json`, `headers`, and the `Response` object (`status_code`, `reason`, `text`, `json`, `headers`, `cookies`) |

---

## ✨ Highlights

### 🌍 `pytz` — Time zones without the headaches
Work with named zones like `America/New_York` and `Europe/Paris` and let the library resolve **daylight saving time** automatically.
- `localize()` *attaches* a time zone to a naïve `datetime` — it does **not** convert it.
- `astimezone()` converts an aware `datetime` between zones, DST included.

### 🧠 `dateutil` — Parse dates the way humans write them
Skip hand-written `strptime` format strings. One call handles ISO 8601, `12/31/2020`, `2020-01-01 10:30:00 am +01:00`, and more.
- Control `Month/Day` vs `Day/Month` ambiguity with `dayfirst`.
- Extract dates from noisy text with `fuzzy_with_tokens=True`.

### 🧾 JSON — The universal data language
Understand how JSON objects, arrays, and values map to Python `dict`, `list`, `str`, `int`, `float`, `bool`, and `None` — and why types like `datetime` and `Decimal` need custom handling during serialization.

### 🔌 REST APIs — Talk to the web programmatically
From the anatomy of a URL to HTTP methods and status codes, then a practical walkthrough of querying a live financial data API.

### 🌐 `requests` — HTTP for Humans
The de facto standard for making HTTP calls in Python, with a far cleaner interface than the low-level standard library.
- Every HTTP verb is a function: `requests.get()`, `requests.post()`, `requests.put()`.
- Pass query parameters, JSON bodies, and headers as plain Python arguments.
- Inspect the `Response` object: `status_code`, `reason`, `text`, `json`, `headers`, `cookies`.

---

## 📈 Continue the Journey — Data Science Libraries

Core libraries for numerical computing, data analysis, and visualization:

| Library | Purpose | Notes |
|---------|---------|-------|
| 🔢 **NumPy** | Efficient array processing and mathematical computation | [NumPy Notes →](#) *([link](https://github.com/Shiva-teja-chary-andhoju/Numpy_Notes))* |
| 🐼 **Pandas** | Data manipulation and analysis | [Pandas Notes →](#) *([link](https://github.com/Shiva-teja-chary-andhoju/Pandas_Notes))* |
| 📊 **Matplotlib** | Plots and charts | [Matplotlib Notes →](#) *([link](https://github.com/Shiva-teja-chary-andhoju/Matplotlib_Notes))* |

---

## 🔮 Coming Soon

This repository is a work in progress. **Many more libraries for data analytics, machine learning, and AI will be added here later**, so star or watch the repo to follow along.

---
