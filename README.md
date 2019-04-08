# browsercrawler-housekeeping
Housekeeping for crawling in the browser aka [`browsercrawler`](https://github.com/eklem/browsercrawler). Keeping track of what has been added to search engine / database, and comparing to page timestamps.

This is to make browsercrawler and i.e. search-index work well together.

## Functionality to be

* [ ] Que of documents added to i.e. a search engine or a db <-- What the user will have available
* [ ] Que of documents to be crawled
  * [ ] Already crawled, true/false
  * [ ] Last crawled date (Just take a string with when web-page was last updated)
  * [ ] Last document crawled (where to pick up for next cycle)
