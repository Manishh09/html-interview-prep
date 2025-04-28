## What are meta tags ?

- Represented with the tag `meta`
- Provides additional information about the web page
- Syntax: 
    ```html
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    ```


## What are the types of meta tags and usages of each ?

1. `<meta charset="UTF-8">` :
    - Should be the first tag under `head` tag in an HTML document
    - Helps on Character Encoding
    - Helps browsers to interpret different chars
    - UTF-8 -> Characters from different languages can be displayed correctly in browser
  
2. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`:
    - Ensures proper rendering and touch zooming on mobile devices.
    - Helps make the website responsive.

3. `<meta name="description" content="Your description here">`:
    - Provides a brief summary of the webpage content.
    - Improves SEO and helps search engines display relevant snippets.

4. `<meta name="keywords" content="keyword1, keyword2, keyword3">`:
    - Specifies keywords relevant to the webpage.
    - Assists search engines in understanding the page's topic.

5. `<meta name="author" content="Manish">`:
    - Tells about author of web page

6. `<meta http-equiv="refresh" content="30">`:
    - Automatically refreshes or redirects the page after a specified time.
    - Useful for timed updates or redirection purposes.
