# disneyDB

Disney Movie Scraping + Database

Small notebook with code to scrape Disney movie data from Wikipedia and save in different formats (JSON, CSV, Pickle (Binary))

## Getting Started

1. Clone the repository

    `$ git clone https://github.com/tintindas/disneyDB.git`

1. Navigate into directory

    `$ cd disneyDB`

1. Set up Python virtual environment

    `$ python3 -m venv .venv`
  
    .venv is what I name my virtual environment folder. 

1. Activate environment
  
    `$ source .venv/bin/activate`

1. Install dependencies
  
    `$ pip install -r requirements.txt`

     **Note - ** You don't need to do any of the above the steps if you're running your jupyter notebook with Anaconda.

1. Run Jupyter Notebook
     
     The dataset_creation.ipynb is broken up into logical cells that can be run in sequence to generate the movie database in json, pickle and csv formats
