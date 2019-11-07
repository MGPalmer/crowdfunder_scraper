# crowdfunder_scraper

This is a small library to scrape data off a (to be unnamed) crowdfunding website. The code is here mostly for instructional purposes.

Please see the accompanying blog posts: https://monogreen.home.blog/2019/11/05/scraping-a-crowd-funding-platform-for-fun-and-non-profit-part-1/

# Usage:

To run a scraper, go into any language-specific subdirectoy:
"$ cd ruby"
Depending on the language, you might need to do setup:
"$ rvm install 2.6.0 && bundle"
Then just run the script from bash with the url to be scraped:
"$ ./scrape_crowdfunder http://example.com"
All scripts should also have options, use the usual to see them:
"$ ./scrape_crowdfunder --help"

# Tests:

Tests are in the top-level directory. Set up the Ruby environment:
"$ rvm install 2.6.0 && bundle"
Then just run it for each implementation:
"$ ./test ruby/scrape_crowdfunder"

Any feedback welcome! Find me on monogreen.de or here on Github.
