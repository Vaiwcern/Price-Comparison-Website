# Scrape and Extract Data Website

This project is a web scraper that retrieves information about laptops, PCs, screens, and other related products from various websites and then stored in a MySQL database hosted on PlanetScale. It allows users to search products by keywords or filter, and compare the specifications, prices, and other details of different products in order to make informed purchasing decisions. The scraper is built using the Selenium and BeautifulSoup libraries and the website is developed using the Flask framework.

You can view the project report [here](report.pdf)

## Features

- Search for laptops, PCs, screens, and related products from multiple websites.
- Retrieve detailed information such as specifications, brand, name, prices and the original shop.
- Compare multiple products side by side.
- Compare prices of the same or similar product across different websites.
- Filter and sort results based on specific criteria (e.g., price range, brand, specifications, etc.).
- User-friendly web interface for easy navigation and interaction.

| Filter by Parameters                                    | Search by Keywords                                   |
|---------------------------------------------------|---------------------------------------------------|
| <img src="./demo/filter.png" width="1000px">     | <img src="./demo/search.png" width="1000px">    |

## Installation

### Clone the repository

```
$ git clone https://github.com/HungBacktracking/Web-Scraper.git
```

### Change into the Website/Scraper directory:

```
$ cd Web-Scraper/website
```

or

```
$ cd Web-Scraper/scraper
```

### Install the required dependencies using pip:

```
$ pip install -r requirements.txt
```

## Usage of Website

Update the information of your database.

Start the Flask development server:

```
$ flask run
```

In flask, default port is 5000.

Open your web browser and go to http://localhost:5000.

Or access the website in your web browser at [thegioilaptop.vercel.app](https://thegioilaptop.vercel.app/Laptop).

## Usage of Scraper

Update the information of your database.

Start the **main.py** file:

```
$ python main.py
```
