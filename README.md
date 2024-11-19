<h2>Steps in the Code:</h2>

**Set Up a Search Request:**

Construct a search query using Google's search URL (https://www.google.com/search?q=).
The num parameter specifies the number of results to fetch per query.

**HTTP Request:**

A GET request is sent to Google with the specified query and a User-Agent header to avoid being blocked.

**HTML Parsing:**

The BeautifulSoup library parses the HTML response.
It searches for the relevant divs that contain search result links.

**Extract Links:**

Finds and extracts the URLs from each search result (<a> tags).
Ensures they are valid URLs before adding them to the result list.

**Keyword**

write your keyword 
