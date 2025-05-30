# Scrape Website using Gradio

<!-- Badges -->
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) [![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](#requirements)  [![Gradio Version](https://img.shields.io/badge/gradio-3.0%2B-orange.svg)](https://gradio.app/)  [![GitHub Issues](https://img.shields.io/github/issues/Rishi-Kora/scrape-website-using-gradio.svg)](https://github.com/Rishi-Kora/scrape-website-using-gradio/issues)  [![GitHub Stars](https://img.shields.io/github/stars/Rishi-Kora/scrape-website-using-gradio.svg)](https://github.com/Rishi-Kora/scrape-website-using-gradio/stargazers)  [![GitHub Forks](https://img.shields.io/github/forks/Rishi-Kora/scrape-website-using-gradio.svg)](https://github.com/Rishi-Kora/scrape-website-using-gradio/network)  



A lightweight Jupyter-based tool and Gradio interface to scrape and visualize website content with minimal setup.

##  Features

- **Easy setup**: One-line install via `pip`.
- **Interactive UI**: Launch a Gradio web app to input any URL and see raw HTML/text output.
- **Notebook demo**: Includes a ready-to-run Jupyter notebook showing how to extend or embed the scraper.
- **Extensible**: Use the core scraping function in your own pipelines or micro-services.

##  Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Rishi-Kora/scrape-website-using-gradio.git
   cd scrape-website-using-gradio


2. (Optional) Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## 🏃‍♂️ Usage

### 1. Run the Gradio App

```bash
python app.py
```

* Open your browser at `http://localhost:7860/`
* Enter any website URL to fetch and display its content.

### 2. Explore the Notebook

Open `scrape_website-updated.ipynb` to see:

* How to call the scraper function programmatically.
* Examples of parsing and visualizing extracted text.

##  Configuration

* **Timeout**: Adjust the HTTP request timeout in `scraper.py`.
* **User-Agent**: Change the default header to mimic different browsers or bots.
* **Output format**: Extend to JSON, CSV or database outputs as needed.

##  Contributing

Contributions, issues and feature requests are welcome!

1. Fork the repo
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Open a Pull Request

##  License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

Rishi Kora – [rishi.kora@example.com](mailto:rishi.kora@example.com)
Project Link: [https://github.com/Rishi-Kora/scrape-website-using-gradio](https://github.com/Rishi-Kora/scrape-website-using-gradio)


