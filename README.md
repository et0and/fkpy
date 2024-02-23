# fkpy
Flesch Kincaid readability script for webpages

Assuming the site that you are running the script against has a sitemap, you can use something like [trafilatura](https://github.com/adbar/trafilatura) to generate a list of urls. 

‘trafilatura --sitemap "https://example.com/sitemap.xml" --list > urls.txt’

Running the script on this urls.txt will produce a CSV output, showing the URL and the corresponding Flesch Kincaid score.  
