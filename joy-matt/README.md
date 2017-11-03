# 09-sql-joins-relations

**Author**: Matt I and Joy
**Version**: 1.0.0

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
Updating the blog website to allow the view to work with the database, including user input values.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
First, set conString. Then, write a SQL query to insert new author and add author and authorURL as data for the query. Then, write query to retrieve author_id by author name for the new article. Then, write query to insert new article to the articles table using the author_id.  Finally, write query to update the authors and articles table by article_id.  

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
languages: HTML, CSS, JavaScript, SQL.
libraries: highlight.pack.js, marked.js, JQuery, Express, Postgres, Bodyparser, Handlebars, icomoon, NodeJS.

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource. -->
11-03-2017 9:00am - Started on Lab with Joy driving
11-03-2017 9:45am - Finished TODO's but some were wrong... got a lot of TA help
11-03-2017 10:45 - Everything works yay
11-03-2017 11:15 - Finished README.md with Matt driving

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
NormalizeCSS - https://necolas.github.io/normalize.css/
jQuery - https://jquery.com
NodeJS - https://nodejs.org/en/
HandlebarsJS - http://handlebarsjs.com/
HLJS - https://highlightjs.org/
MarkedJS - https://github.com/chjj/marked
ExpressJS - https://expressjs.com/
IcoMoon - https://icomoon.io
Body Parser - https://github.com/expressjs/body-parser
Postgres - https://www.postgresql.org/
Ron, Allie, and Dustin
