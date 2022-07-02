wiki-scraper

Table of Contents
Installation
Usage
Requirements
Installation
Clone the git repository:

git clone https://github.com/nirantak/scraper.git && cd scraper
cp -nv .env.sample .env  # copy and update the env variables
Install necessary dependencies

python3 -m venv .venv
source .venv/bin/activate
pip install -U pip wheel setuptools
pip install -U -r requirements.txt
playwright install
Usage
See scrapers/README.md for usage instructions.