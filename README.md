# job-trends-analyzer

# Overview:
The Job Trends Analyzer is a full-stack Python-based web application that scrapes job listings from public APIs, stores them in a PostgreSQL database, and generates insights like top skills, job roles, and posting trends. Users can view data through a Flask + Bootstrap frontend and receive weekly summaries via Telegram. The project is containerized and automated with GitHub Actions.

# Tech Stack:
Backend: Flask

Scraper: BeautifulSoup or requests + lxml / Scrapy

Data Analysis: Pandas, NumPy

Visualization: Plotly, Seaborn, or Dash/Streamlit

Frontend: Bootstrap 5, Jinja2 (Flask templates)

Database : PostgreSQL

CI/CD: GitHub Actions

Docker: Dockerize scraper + app

Deployment: Azure App Service / Render / Fly.io