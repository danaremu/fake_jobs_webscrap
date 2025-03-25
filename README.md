# ETL (Extract, Transform, Load) Script

## Description

This project is an ETL (Extract, Transform, Load) script that scrapes job listings from a webpage, processes the data, and prepares it for analysis. The script utilizes Python libraries such as `pandas`, `BeautifulSoup`, and `requests` to extract and clean job data.

## How to Run the Script

### Prerequisites

Ensure you have Python installed along with the required dependencies. You can install them using:

```bash
pip install pandas numpy beautifulsoup4 requests
```

### Running the Script

1. Clone this repository or download the script.
2. Open a terminal and navigate to the project directory.
3. Run the script using:

```bash
python etl_script.py
```

### Example Code Snippet

```python
import pandas as pd
import numpy as np
from bs4 import BeautifulSoup
import requests
import xml.etree.ElementTree as ET

# Define global variables
global URL, HEADERS

URL = "https://realpython.github.io/fake-jobs/"
HEADERS = {"User-Agent": "Mozilla/5.0"}
JOBS = []
```

## Output

The script extracts job data and outputs it as a structured dataset (DataFrame or list of dictionaries), making it easy to analyze or export for further processing.
"# fake_jobs_webscrap" 
