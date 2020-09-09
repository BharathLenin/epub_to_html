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
    pandoc -s --toc -c template/pandoc.css -A template/footer.html test1.epub -o demo/example.html
    ```

## References
* https://pandoc.org
* https://opensource.com/article/18/10/book-to-website-epub-using-pandoc
