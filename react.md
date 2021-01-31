

#### 1. Why is the scrapy spider class crawlspider good for generic website crawling?
- [x] It comes with generic mechanisms for crawling links by a set of predefined common rules.
- [] It contains a skeleton class that does not contain a predefined set of rules, which is good for complicated sets that require customization
- [] It comes with un-customizable mechanisms for crawling links by a long list of rules.
- [] It comes with specific mechanisms for crawling links by a set of predefined custom rules.


#### 2. What do the following lines of code produce?
```python
soup = Beautiful Soup(""" <p> <a href="https: //www.wikipedia.org'>link </a></p>""")
soup.find('a')
```
- [] https://wmw.wikipedia.org
- [x] <a href="https://www.wikipedia.org">link </a>
- [] >link
- [] <h1> Wikipedia </h1>


#### 3. Which code snippet will create a custom pipeline class that will return a warning when no header is found in the SpiderPerson spider, but -will still return the item
- [x] class pipelineProcessorWarning(object):
```python
def process_item(self, item, SpiderPerson):
SpiderPerson. logger .warn('{@}'.format(item.get('header', 'No header was found')))
return item
```
- [] class pipelineProcessorWarning(item) :
```python
def processer_item(SpiderPerson):
SpiderPerson.logger.warn('{0}'.format(item.get('header', 'No header was found')))
```
- [] class pipelineProcessorWarning(object):
```python
process_item(self, item, SpiderPerson):
SpiderPerson.logger.warn('{0}'.format(item.get('header', 'No header was found')))
return object
```
- [] Function(pipelineProcessorWarning(object)) :
```python
method class process_item(self, item, SpiderPerson):
SpiderPerson. logger .warn('{@}'.format(item.get('header', 'No header was found')))
return object
```


#### 4. What is true regarding overriding pipeline methods?
- [] nly one method can be overridden when using Beautiful Soup
- [x] All pipeline methods can be overridden
- [] nly private pipeline methods can be overridden
- [] nly the data store method can be overridden


#### 5. You create a web scraping application that uses Beautiful Soup to scrape information from a media webpage. A co-worker uses a different scraping library to -scrape the same webpage; however, their resulting dataset is
different than yours. How could this have happened
- [] Different versions of Python create different parsed documents.
- [] Different web standards could create different parsed documents.
- [x] Different parsers create different HTML/XML documents.
- [] Different versions of Beautiful Soup create different parsed documents.


#### 6. Why is Beautiful Soup preferred for scraping static pages when Selenium could be used for everything?
- [] Developing code with Beautiful Soup is much easier to scrape static pages than it is with Selenium
- [] Beautiful Soup renders static pages better when compared to Selenium.
- [] Selenium takes more time while scraping static pages than Beautiful Soup.
- [x] While scraping static pages, it is not necessary to render it in a browser.


#### 7. Which type of classes can be defined in Scrapy to scrape data from a website?
- [] Knife Class
- [] Scratch Class
- [] Crawler Class
- [x] Spider Class


#### 8. What is currently the only supported parser in Beautiful Soup for dealing with extensible markup language?
- [] html. parser
- [] json.parser
- [] htm151ib
- [x] Lxml-xml


#### 9. What Ixml method would allow us to find HTML page elements?
- [] XMLSchema
- [x] XPath
- [] RelaxNG
- [] Schematron


#### 10. You need to find all 'hl' header attributes in a web page. How can this be accomplished using Beautiful Soup?
- [] soup.find_all('hi'.[attrs]) to return all hl headers attributes.
- [x] soup.find_all('h1').attrs to return all hl header attributes.
- [] soup.find_all('h1').[attribute] to return all hl headers attributes.
- [] soup.find('h1').attrs to return all hl header attributes.


#### 11. Which line of code is next when trying to discover the content type?
```python
r = requests.get('https://api.github.com/user', auth=('user', 'pass'))
```
- [] r.['content-type']
- [] return ['content-type']
- [x] r.headers[ 'content-type']
- [] r.get['content-type']


#### 12. You start web scraping several sites with Beautiful Soup and notice that much of the data you received is malformed or has no HTML body. If -you are using the default HTML parser, what could you do to improve your parsing
- [] Scan other web pages. The HTML tags in their web sites are malformed, causing the parser to fail
- [] Import Ixml's XML parser. It is more lenient on XML elements and can better handle broken XML tags.
- [] Import Python's HTML parser. It is more lenient on HTML elements and can better handle broken HTML tags.
- [x] Import Ixml's HTML parser. It is more lenient on HTML elements and can better handle broken HTML tags.


#### 13. When attempting to download a media file using the built-in Python library urllib.request , what step comes after opening the URL file?
- [] Read the file with .ingest()
- [x] Read the url file with .read()
- [] Parse the file with .parse()
- [] Save the file with .save()


#### 14. Which procedure generally does not apply to web scraping analytical data from a web page?
- [x] Importing data into a web page using the urllib library
- [] Accessing the tag names of the HTML using name
- [] Exporting results to an external files, such as a CSV, XML, or JSN
- [] Cleaning HTML data by stripping or replacing unnecessary data


#### 15. What is a supported parser for Beautiful Soup?
- [] Iparser
- [x] html.parser
- [] htmllib
- [] xml.parse


#### 16. When might you want to use the html5lib parser with Beautiful Soup?
- [x] To create valid objects from HTML5 when parsing
- [] To parse newer page elements like XML and JSN
- [] To parse older page elements like headers and lists
- [] To avoid external library dependencies


#### 17. How could you add exception handling to check if your Beautiful Soup parser is unable to connect to a website?
- [] Check for an HTTP status code of 200. If it's true, throw an exception.
- [x] Check for an HTTP status code of 200. If it's false, throw an exception
- [] Check for an HTTP status code of 101. If it's true, throw an exception.
- [] Check for an HTTP status code of 400. If it's false, throw an exception.


#### 18. You need to search through a long HTML document and find all of the mentioned numbers. How could you utilize Beautiful Soup and regex to -parse for this specific data
- [] Use Beautiful Soup's find_all() method to look for values with a regex of (\s) or [\t\n\r\f\v] to grab all decimal values.
- [] Use Beautiful Soup's find_all() method to look for values with a regex of (\W) or [^a-zA-Z0-9_] to grab all decimal values.
- [] Use Beautiful Soup's find_all() method to look for values with a regex of (\D) or [^0-9] to grab all decimal values.
- [x] Use Beautiful Soup's find_all() method to look for values with a regex of (\d) or [0-9] to grab all decimal values.