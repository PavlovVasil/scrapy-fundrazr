# scrapy-fundrazr

A simple web crawler shown in [this](https://www.codementor.io/mgalarny/using-scrapy-to-build-your-own-dataset-cz24hsbp5) blog post.

The actual GitHub repo is [here](https://github.com/mGalarnyk/Python_Tutorials/tree/master/Scrapy/fundrazr).

## How to run the scraper
I am using Python 3.7 when running the crawler, so it has to be installed on your system.
To restore the environment do the following:

1. [Download](https://www.anaconda.com/distribution/) and install Anaconda
2. Open Anaconda terminal (or Anaconda Powershell)
3. Navigate to the root project directory
4. Run ```conda env create -f environment.yml``` - this would restore the enviroment and dependencies
5. Run ```conda activate scrapyEnv``` in order to activate the environment
6. Run ```scrapy crawl fundrazr_crawler -o MonthDay_Year.csv``` - this would actually run the crawler and generate an .csv file containing the data scraped from Fundrazr, as shown in the tutorial

## How to debug the scraper if you are using VS Code
Either use the provided launch.json debug configuration, or run the runner.py in the VS Code debugger and it would launch the crawler. 