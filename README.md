# NewsScraping

### Overview
 Created a web app, using Food Network Website, that lets users view and leave comments on the latest news. It used Mongoose and Cheerio packages to scrape news from Food Network.

 ## How the app works

* Create an app that accomplishes the following:

  1. Whenever a user visits the site, the app should scrape stories from the news outlet and displays them for the user. Each scraped article is saved to the application database. The app scrapes and displays the following information for each article:

     * Headline - the title of the article

     * Summary - a short summary of the article

     * URL - the url to the original article

     * Image - image to the article

  2. Users can also leave comments on the articles displayed and revisit them later. The comments can be saved to the database as well and associated with their articles. Users should also be able to delete comments left on articles. All stored comments are visible to every user.


### Technology Used:
 
   1. express

   2. express-handlebars

   3. mongoose

   4. cheerio

   5. axios

   6. Heroku Server

   

3. **NOTE**: If you want to earn complete credit for your work, you must use all five of these packages in your assignment.

4. In order to deploy your project to Heroku, you must set up an mLab provision. mLab is remote MongoDB database that Heroku supports natively. Follow these steps to get it running:

5. Create a Heroku app in your project directory.

6. Run this command in your Terminal/Bash window:

* `heroku addons:create mongolab`










