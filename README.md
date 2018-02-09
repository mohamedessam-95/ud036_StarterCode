# Movie Website :
Source code for a Movie Trailer website.

# Requirements :
You must have python installed on your machine https://www.python.org/

# Installation :
Download each of these files and put them in the same directory :
 
 1 - media.py
 
 2 - entertainment_center.py
 
 3 - fresh_tomatoes.py
 
 ----> Then double click on entertainment_center.py to invoke the python server-side code and open the website
 
 # Usage :
 The website is easy to use , you can scroll down to see the movie posters and click on any of them to view it's trailer
 
 # Change log :
 The fresh_tomatoes.py is provided with more css rules and background image
 
 # Technical information :
 
   media.py : It contains the movie class definition that will hold individual information of each movie object when instantiated
   
   entertainment_center.py : It contains the movie objects of each individual movie and it collects them in a list and passes them into open_movies_page() function that resides in fresh_tomatoes
   
   fresh_tomatoes.py : It contains the actual html code and css rules along with some python server-side code that extracts the movie objects and put them in a showcase
