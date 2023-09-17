# YouTube Top Streamers Analysis

## Overview

This project is focused on scraping data from the [HypeAuditor website](https://hypeauditor.com/es/top-youtube/) to analyze the top YouTube streamers. It gathers information about streamers' rankings, usernames, categories, subscribers, countries, visit counts, likes, comments, and channel links.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Data](#data)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, you'll need to clone the repository to your local machine. Follow the instructions below:

```bash
git clone https://github.com/your-username/youtube-top-streamers-analysis.git
cd youtube-top-streamers-analysis
```


## Prerequisites

Make sure you have the following prerequisites installed on your system:

- Python 3
- pip (Python package manager)

You can install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```
## Usage

You can run the data scraping and analysis by executing the main Python script:

```bash
python scrape_data.py
```

## Data

The data collected includes the following columns:

- Rank
- Username
- Categories
- Subscribers
- Country
- Visits
- Likes
- Comments
- Links

## Data Cleaning


Data cleaning is an essential step to ensure accurate analysis. We handle missing values and normalize categories for better analysis.

## Data Analysis


We perform various analyses on the collected data, including:

- Ranking distribution
- Popular categories
- Subscribers and visit trends
- Geographic distribution
- Engagement metrics

You can explore these analyses in the Jupyter Notebook `data_analysis.ipynb`.

## Contributing


Contributions to this project are welcome. You can contribute by:

- Reporting issues
- Providing bug fixes
- Adding new features
- Improving documentation

## License


This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


