# IMDB Top Rated Movies Web Scraping

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Collected](#data-collected)
- [Contributing](#contributing)
- [Support](#support)

## Introduction
This Jupyter Notebook project is aimed at extracting data from the IMDB website for the top-rated movies using web scraping techniques. We will gather information such as movie name, ratings, release dates, num_of_likes, duration from the IMDB website. This README file provides an overview of the project, its requirements, and instructions on how to use the provided Jupyter Notebook.

## Requirements
Before you can run the Jupyter Notebook in this project, make sure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- Beautiful Soup 4
- Requests
- Pandas

You can install these dependencies using pip:

```bash
pip install jupyter beautifulsoup4 requests pandas
```

## Getting Started
1. Clone this repository to your local machine:

```bash
git clone https://github.com/saurav-sabu/imdb-top-rated-movies-jupyter.git
```

2. Navigate to the project directory:

```bash
cd imdb-top-rated-movies-jupyter
```

3. Install the required dependencies as mentioned in the requirements section.

## Usage
1. Open a terminal or command prompt and navigate to the project directory.

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. In your web browser, you'll be able to access the Jupyter Notebook interface. Navigate to the `IMDB_Top_250_Movies.ipynb` file and open it.

4. Run the cells in the Jupyter Notebook to start scraping IMDB top-rated movies data.

5. The notebook will guide you through the scraping process, and you can execute the cells one by one.

6. Once the scraping is complete, the data will be saved to a CSV file named `movies.csv`.

## Data Collected
The Jupyter Notebook will scrape the following data for each movie:

- movie_name
- release_year
- duration
- rating
- num_of_likes

The scraped data will be saved in a CSV file for further analysis or use.

## Contributing
If you would like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test them.
- Create a pull request with a clear description of your changes.

## Support

If you have any questions, encounter issues, or need assistance, you can contact at saurav.sabu9@gmail.com. I am here to help you with any inquiries or problems you may have.