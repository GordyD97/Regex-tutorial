# Regex-tutorial

# Table of contents
    -[Description] (# Description)
    -[Test String] (# Regex search string)
    -[example regex] (# example regex)
    -[Summary] (# Summary)
# Description
     ```
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile
```
## Regex search string
-^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$
## example regex 
[link] (https://www.pinkbike.com/news/eurobike-2022-exciting-products-from-european-manufacturers-part-2.html)

## Summary
I the developer used the regex search function to identify a valid url. In this tutorial the regex capture groups will be explained in order of what they are. Each token that is used in the search string will be identified and defined in the tutorial as well. Through out the tutorial the user will be promopted with information reagarding to the regex search function. 

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

