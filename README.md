# ScrapeCity
GTBC Homework 18 MongoDB &amp; Mongoose
# All the News That's Fit to Scrape

### Overview:

A web app that lets users view and leave comments on the latest news stories. Cheerio scrapes the news source of site and stores favorite stories and comments on stories to MongoDB.

### To Start:

1. Run `npm init`. When that's finished, install and save these npm packages:

   1. express

   2. express-handlebars

   3. mongoose

   4. cheerio

   5. axios

2. This app is deployed on Heroku. mLab is remote MongoDB database that Heroku supports natively. Follow these steps to get it running:

3. Create a Heroku app in your project directory.

6. Run this command in your Terminal/Bash window:

* `heroku addons:create mongolab`

* This command will add the free mLab provision to your project.

7. When you go to connect your mongo database to mongoose, do so the following way:

## About ScrapeCity

* ScrapeCity accomplishes the following:

  1. The app scrapes stories from the news source and displays the stories for the user. Each scraped article can be saved to the application's database. The app scrapes and displays the following information for each story:

     * Headline - the title of the story.

     * Summary - a short summary of the story.

     * URL - the url to the original story.

  2. Users are able to leave comments on the stories displayed and can revisit them. The comments saved to the database and are associated with the stories. Users can also delete the comments left on stories. All stored comments are visible to every user.

### Helpful Links

* [MongoDB Documentation](https://docs.mongodb.com/manual/)
* [Mongoose Documentation](http://mongoosejs.com/docs/api.html)
* [Cheerio Documentation](https://github.com/cheeriojs/cheerio)

