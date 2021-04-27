# pagerank
 A mini search engine based on google page-rank algorithm.
 
## Project description
This project is the last course on Python for Everybody Specialization on Coursera. Here, we implement a web crawling application to crawl through a given website and gather all the hyperlinks it can come across and automatically move to the next hyperlink in the page and collect other hyperlinks and simultaneously store them in a sqlite3 database. Then, the collected web-pages are ranked according to the early google page-rank algorithm and a visualization is produced from it.

### Files in the project
<ul>
 <li>spider.py: web crawling program and stores the result in a database</li>
 <li>sprank.py: implementation of page rank algorithm</li>
 <li>spjson.py: loads the data to json </li>
 <li>spdump.py: fetches the data from database</li>
 <li>spreset.py: resets the rank to 1 in database</li> 
 <li>force.html: visualizes the data with the help of force.js </li>
</ul>
