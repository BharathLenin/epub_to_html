---
title: EPub to HTML conversion
...


# EPub to HTML conversion


## Installation

1. Install the panda command line tool, 
https://pandoc.org/installing.html


## Commands

1. Check if the pandoc is installed using the command,
    ```
    pandoc --version
    ```
2. Generate the static html from epub file by running the below command,


    ```
    pandoc testEPubFile.epub -f epub -t html -s -o testHtml.html
    ```

## References
* https://pandoc.org
* https://opensource.com/article/18/10/book-to-website-epub-using-pandoc