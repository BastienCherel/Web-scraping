# Web-scraping

## Project Overview

This project investigates the toxicity of comments on TripAdvisor for hotels and restaurants. Using web scraping techniques, the project gathers review data and analyzes the proportion of toxic comments. The analysis compares the toxicity of restaurant and hotel reviews to determine if comments about restaurants are generally more toxic than those about hotels.

The methods involve fetching URLs and ratings for both hotels and restaurants using **APIFY** APIs, extracting comments, and determining their toxicity using **GPT-4o-mini**. The project culminates in a proportional analysis to compare toxicity between the two categories.

## Methods

- **Data Collection**: 
  - The project uses **APIFY** to fetch URLs and ratings for hotels and restaurants.
  - It uses **scrapegraphai** to extract comments from these sources.
  
- **Toxicity Detection**:
  - **GPT-4o-mini** is used to classify whether a comment is toxic or not.

- **Data Analysis**:
  - A proportional analysis is performed to determine if reviews about restaurants are more toxic than those about hotels.

## Acknowledgments

- APIFY for providing the API for fetching hotel and restaurant reviews.
- scrapegraphai for scraping and extracting comments.
-	GPT-4o-mini for classifying the toxicity of comments.



## How to Run

1.	Clone the Repository

Clone this repository to your local machine.

```bash
git clone https://github.com/BastienCherel/Web-scraping.git
cd Web-scraping
```

2.	Install Dependencies

Ensure that you have the required dependencies by running:

```bash
pip install -r requirements.txt
```

3.	Run the Jupyter Notebook

Open the Jupyter notebook in your preferred environment and execute the cells.


## Authors

- [Bastien Cherel](https://github.com/BastienCherel)  

- [Shangzhi Lou](https://github.com/ShangzhiLou)  
