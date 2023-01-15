# scrap_imgur_image_links-python

## What does this repo do?
U input an url link with multiple pics, then u can get a .txt file, containing all the .jpeg image links on that page

## Reason
So i found out that imgur has updated to a new version, which is the pic below.

![My Remote Image](https://i.imgur.com/wsrM9z1.jpg)

Different from the old one, u cant generate multiple links at a time, so this py is here to solve the problem

input the url link, and choose the name of the txt file in the last cell (PS: 'string'), then run the program

so the txt file will be automatically saved

sth like this
![My Remote Image](https://i.imgur.com/qOnW5tu.png)

## others
remember to prepare chromedriver since we are using selenium

use different import depending on ur selenium version (me is 4

add user-agent, cookies, authorization etc. if needed

## improvements?
i am not cs major nor experienced developers (i know a bit py just because i do ML), so i am also thinking a way to improve (like using beautiful soup), but seems that this a a dynamic webpage, and scroll down is needed to get more links, so hope that i can figure out a way to do it using static ways

welcome to all improvements and discussions

