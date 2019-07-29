# instagram-scraper

Instagram Scrape by Tag

NodeJS application for scraping posts from Instagram by hashtag without API access.

# Config
Setup default tag and limit in `config/defaults.js`
    
// VARIABLES
INSTAGRAM_DEFAULT_HASHTAG: 'landscape',
INSTAGRAM_DEFAULT_FIRST: 10
<br>
# Setup
npm install
npm start
<br>
# Run Server
http://localhost:3000
For top most posts
<br>
http://localhost:3000/<tag>
For recent posts
<br>
http://localhost:3000/<tag>?recent=1
