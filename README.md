# WebMap

A program that takes a webpage, takes all of its embeded links, and recursively derives more webpages with BFS.

## How to run

Compiled .jar:

    java -jar WebCrawler.jar (SessionName) (Mode) (RecursionAmount) (URLs)

Compiled .exe:

    crawl (SessionName) (Mode) (RecursionAmount) (URLs)
  
 - a session can be named whatever you want, and inputting the name of a previous session whould continue that session's computation.
 - RecursionAmount must be integer. It determines how many sites the program will process.
 - Multiple URLs could be placed at the end with a space seperator. It adds urls to a new or existing queue.
 
Requires JRE 15 to run

Libraries used:
 - https://github.com/jhy/jsoup/ MIT License
 - https://github.com/apache/commons-collections Apache 2.0 Licence
