# 🌐 WebSummarizer

WebSummarizer is a Python tool that fetches the contents of a given website and a concise, markdown-formatted summary using OpenAI's GPT API.
It is designed to ignore navigation and other irrelevant text, focusing on meaningful content.

- 🌍 Fetches and renders dynamic web content using `requests-html`.
- 🧹 Cleans and processes web page text.
- 🧠 Uses OpenAI GPT model (`gpt-4o-mini`) to generate summaries.
- 📝 Outputs the summary in Markdown format.
- 🛠️ Async architecture for efficient web scraping and API usage.

 
 ## Installation

First, clone the repository:

```bash
git clone https://github.com/shikisvoid/WebSummarizer.git
cd WebSummarizer
```


Requirements:

```bash
pip install requests requests-html beautifulsoup4 python-dotenv openai lxml_html_clean
```


Setup:

```bash
OPENAI_API_KEY = your_api_key_here
```

Usage:

```bash
await display_summary("https://example.com")
```

