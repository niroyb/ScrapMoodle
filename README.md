ScrapMoodle
=================

This program recursively downloads all the files from the course pages on Moodle.
Dependencies are [lxml]

There is also a utility class "scraptools" to group common scraping operations:
* getDOM : Returns the DOM element of the page for the given url
* getElementsFromHTML : Returns a list of lxml elements from html source corresponding to a cssSelector
* getElementsFromUrl : Returns a list of lxml elements from the page fetched at url corresponding to a cssSelector
* getUrlContent : Gets the content of a url as a string
* downloadResource : Download the content of a  url to the disk
* saveResource : Saves data to file in binary write mode
* urlIterator : Successively yields page urls while there is a next one found by the cssSelector