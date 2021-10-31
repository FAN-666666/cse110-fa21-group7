This is a space for all the bakground research we have done so far to build a recipe app.

**What is a recipe?**

A set of instructions for preparing a particular dish, including a list of ingredients required.

**What is a recipe app?**

An application to assist cooks in their culinary journey and their day-to-day kitchen adventures.
Recipe apps are a broad field but it has the following "nice-to-have" functionality:
- TBD


**Format**  
- Name  
- Brief description - usually one line  
- Metadata - prep time, calories, macro information
- Ingredient List 
- Cooking instructions either in video or step-by-steo bullet form
- Reviews left by other users

**Recipe JSON-LD model**

JSON-LD is a specialized verison of the JSON data structure for linked data. It's used to easy
parsing of data from websites and to promote as search results. It makes your website easier to
index for a search engine's web scraper.

Coming soon

**APIs for getting recipes**

recipe-scraper

A NodeJS package for scraping recipes from a wide array of websites.  Free to use, we just need to import the scripts for specific websites.  Returns a recipe object with name, ingredients, instructions, image, time, etc.  Has error handling and was last updated 5 months ago.

https://github.com/jadkins89/Recipe-Scraper#readme


Allrecipes Scraper

Apify actor for extracting data about actors from Allrecipes. It allows you to extract all recipes for the given search text and/or the given list of start urls. Requires Apify SDK which has a free service for limited usage.  

https://github.com/dtrungtin/actor-allrecipes-scraper




