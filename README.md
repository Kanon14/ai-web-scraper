# ai-web-scraper

## Overview
This is a simple project focuses on web-scraper with an LLM model prompting for information retrieval.

## Project Setup
### Prerequisites
- Python 3.10+
- Compatible cuda toolkit and cudnn installed on your machine
- Anaconda or Miniconda installed on your machine
- A chromedriver installed on your machine
- An ollama installed on your machine. [[download link](https://ollama.com/download)]
- Install LLM model compatible with your machine, information cab be found in [Ollama](https://github.com/ollama/ollama)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Kanon14/ai-web-scraper.git
cd ai-web-scraper
```

2. Create and activate a Conda environment:
```bash
conda create -n ai_web_scraper python=3.10 -y
conda activate ai_web_scraper
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
```bash
streamlit run main.py
```