# 🐝 ScrapingBee Alternative

> Free open-source ScrapingBee alternative - headless browser scraper

[![Python 3.11+](https://img.shields.io/badge/Python-3.11+-blue?style=flat-square&logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/data-scrape/scrapingbee-alternative?style=flat-square)](https://github.com/data-scrape/scrapingbee-alternative)
[![Forks](https://img.shields.io/github/forks/data-scrape/scrapingbee-alternative?style=flat-square)](https://github.com/data-scrape/scrapingbee-alternative/forks)

<a href="https://www.coreclaw.com/?utm_source=github&utm_medium=cpc&utm_campaign=L7&utm_term=&utm_id=L7"><img src="https://img.shields.io/badge/Sponsored%20by-CoreClaw-7B2D8B?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAyTDIgN2wxMCA1IDEwLTV6TTIgMTdsMTAgNSAxMC01ek0yIDEybDEwIDUgMTAtNXoiLz48L3N2Zz4=" alt="Sponsored by CoreClaw" width="200"></a>

## 📖 Overview

**ScrapingBee Alternative** is a free, open-source Python scraper for **ScrapingBee Alternative**. Extract structured data from scrapingbee alternative with full pagination support, proxy rotation, and multiple export formats.

scrapingbee alternative, scrapingbee free alternative, web scraping api

## ✨ Features

- ✅ Headless browser rendering
- ✅ JavaScript execution support
- ✅ Proxy rotation network
- ✅ Screenshot capture
- ✅ No API credits needed
- ✅ Python & REST interface

## 🚀 Quick Start

### Installation

```bash
git clone https://github.com/data-scrape/scrapingbee-alternative.git
cd scrapingbee-alternative
pip install -r requirements.txt
```

### Basic Usage

```bash
python scraper.py "Scrape React SPA with infinite scroll"
```

### Advanced Usage

```bash
python scraper.py "Scrape React SPA with infinite scroll" \
  --output results \
  --format json \
  --max-results 100 \
  --proxy http://user:pass@host:port
```

## 📊 Data Fields

Extracted data includes the following fields:

`url` | `status_code` | `content` | `screenshot_path` | `javascript_result` | `proxy_used` | `timestamp`

## 💡 Use Cases

- JavaScript-heavy page scraping
- Migrating from ScrapingBee
- SPA & React app scraping
- Screenshot automation
- Dynamic content extraction

## 🔧 Configuration

| Option | Default | Description |
|--------|---------|-------------|
| `--output` | `output` | Output file prefix |
| `--format` | `json` | Output format: `json`, `csv`, or `both` |
| `--max-results` | `50` | Maximum results to scrape |
| `--proxy` | None | Proxy URL for IP rotation |
| `--quiet` | False | Suppress info output |

## 📝 Example Output

```json
{
  "url": "https://example.com/result/123",
  "title": "Example Result",
  "data": {
    "rating": 4.5,
    "reviews": 1280,
    "category": "Example Category"
  },
  "scraped_at": "2026-08-05T14:30:00"
}
```

## ⚠️ Disclaimer

This tool is for educational and research purposes only. Users are responsible for complying with the target website's Terms of Service, robots.txt, and applicable laws. The authors of this project are not responsible for any misuse of this tool.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💎 Sponsored by CoreClaw

This project is sponsored by [**CoreClaw**](https://www.coreclaw.com/?utm_source=github&utm_medium=cpc&utm_campaign=L7&utm_term=&utm_id=L7) — the all-in-one web scraping and data extraction platform.

<a href="https://www.coreclaw.com/?utm_source=github&utm_medium=cpc&utm_campaign=L7&utm_term=&utm_id=L7">🌐 Visit CoreClaw.com</a>

---

⭐ If this project helped you, please give it a star!

<!-- CROSS_LINKS_START -->
<!-- Cross-links will be inserted here -->
<!-- CROSS_LINKS_END -->
