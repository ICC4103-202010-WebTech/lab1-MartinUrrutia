Answers:

3-describe the structure of the document,How is the list of news articles structured with HTML?
 
Observing the structure of the document HTML, it is possible to see that it is structured 
in a way that first describes the top of the web page, then describes the composition of the news,
and then describe the bottom of the website, so it is a logical order. 

To structure the list of news, the "body" part of the code have a lot of subclasses, in which
each news item is described with characteristics such as the name, class, style, dimensions of the text,
an own id and a link that connects directly to the news.
For the rest of the website it is similar but more focused on aesthetics.

4- hn.js and news.css. How are these files different? What is their purpose?

The hn.js file contains many different functions, which serve for the website to function correctly,
and allow the user to use the website without errors. 
Each function has a different purpose to execute website actions. 
For example there are functions to handle the classes, like byClass, hasClass, addClass, remClass.
which are used to obtain the elements of a class, search for a class, add a class and remove a class.
Other function like "vote", it serves to give a vote to a news item and it gets more relevance, or the
function "hide", that serves to hide a news that is not of your interest.

The news.css. it is different, this file it is to adjust everything visual on the website, 
such as the sizes of each thing, the colors, the images and the dimensions that fit in the page.
This can be applied for example to a title.



5- How many requests has it taken for the browser to download the Hacker News main page? 

The statistics of the tool show that it takes 7 requests, and 52.5 KB  of resources loaded by the page.

-What are the HTTP request methods in each case?
I'm going to respond in order from top to bottom with a summary of what each method does:

name: favicon.ico - request method: GET - is used to retrieve information from the given server using a given URI
name: grayarrow.gif - request method: GET
name: hn.js?S5Ty60GFbTgUrObD86p - request method: GET
name: news.css?S5Ty60GFbTgUrObD86pQ - request method: GET
name: news.ycombinator.com - request method: GET
name: s.gif - request method: GET
name: y18.gif - request method: GET

This website use the nginx server. 



