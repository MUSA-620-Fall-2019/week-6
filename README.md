# Week 6<br>Getting Data Part 2: Web Scraping

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/week-6/master?filepath=lecture-6.ipynb)

## Updating your local environment

There are a few new packages we'll need for web scraping this week so we'll need
to update your Python environment. The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## New Packages

- [Requests](http://docs.python-requests.org/en/master/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Selenium](https://selenium-python.readthedocs.io)

## Useful Links and Reference Materials

- [Insights into Housing Markets from Scraping Craigslist](https://geoffboeing.com/2016/08/craigslist-rental-housing-insights/)
  - [and accompanying academic article](https://arxiv.org/pdf/1605.05397.pdf)
- [HTML tutorial](https://www.w3schools.com/html/html_intro.asp)
  - sections: introduction, basics, elements, attributes
- [Tutorial on Web Scraping with Requests and BeautifulSoup](https://www.learndatasci.com/tutorials/ultimate-guide-web-scraping-w-python-requests-and-beautifulsoup/)
- [CSS Selectors](https://www.w3schools.com/cssref/css_selectors.asp)
- [101 Web Scraping Exercises](https://github.com/stanfordjournalism/search-script-scrape)
