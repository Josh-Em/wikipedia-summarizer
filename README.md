# Wikipedia Article Summarizer 📚

A Python-based tool that scrapes Wikipedia articles and generates concise summaries using OpenAI's GPT model.

[![Watch the Tutorial](https://img.youtube.com/vi/_XFsVAyjGEc/maxresdefault.jpg)](https://www.youtube.com/watch?v=_XFsVAyjGEc)

## 🎯 Overview

This project demonstrates how to:
- Scrape content from Wikipedia articles using BeautifulSoup
- Process and clean the extracted text
- Generate concise summaries using OpenAI's GPT model
- Handle API interactions and web scraping in a modular way

## 🚀 Features

- Clean text extraction from Wikipedia pages
- Removal of unwanted elements (scripts, styles, tables, etc.)
- Error handling for invalid URLs and failed requests
- Configurable API settings for OpenAI integration
- Modular code structure for easy maintenance

## 📋 Prerequisites

- Python 3.x
- Google Colab account (for running the notebook)
- OpenAI API key

## 🛠️ Required Libraries

```bash
pip install beautifulsoup4 requests openai
```

## 💻 Usage

1. Open the notebook in Google Colab
2. Add your OpenAI API key
3. Run all cells
4. Input any Wikipedia URL to get a summary

Example:
```python
url = "https://en.wikipedia.org/wiki/Mesopotamia"
text = scrape_wikipedia(url)
summary = get_summary(text)
print(summary)
```

## 🔗 Important Links

- [OpenAI Platform](https://platform.openai.com/docs/overview)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
- [Claude AI](https://claude.ai/)
- [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## ⚠️ API Key Security

Remember to:
- Never commit API keys to version control
- Use environment variables or secure key management
- Rotate keys regularly
- Monitor API usage

## 🤝 Contributing

Feel free to:
- Fork the repository
- Create a feature branch
- Submit pull requests
