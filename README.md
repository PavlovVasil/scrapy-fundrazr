# scrapy-fundrazr

A simple web crawler shown in [this](https://www.codementor.io/mgalarny/using-scrapy-to-build-your-own-dataset-cz24hsbp5) blog post.

The actual GitHub repo is [here](https://github.com/mGalarnyk/Python_Tutorials/tree/master/Scrapy/fundrazr).

## How to run the scraper
To restore the enviroment do the following:

1. [Download](https://www.anaconda.com/distribution/) and install Anaconda
2. Open Anaconda terminal (or Anaconda Powershell)
3. Navigate to the root project directory
4. Run ```conda env create -f environment.yml``` - this would respore the dependencies
5. Run ```conda activate scrapyEnv``` in order to activate the environment
6. Run ```scrapy crawl fundrazr_crawler -o MonthDay_Year.csv``` - this would actually run the crawler and generate an .csv file containing the data scraped from the Fundrazr site (as shown in the tutorial)