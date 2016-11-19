# Algolia_Prototype

In this project, I develop a Search experience for a restaurant client, using the Algolia API. 

Evaluation Criteria Addressed: 

1) Overall look'n'feel of the demo: relevance, UI & UX
2) Quality of the code: legibility and re-usability
3) Attention given to details

1a) UI / UX

I began this project by recreating the mockup I was given in Sketch. I also included a link to the Sketch file in this Github. 
Here are a few of the changes I made: 

• I took out the background because I wanted to show the search occuring in the context in which it would actually occur: inside a client's navigation bar. After investigating what common search patterns were from sites like Yelp, Product Hunt, and others, I decided to implement the search bar in a nav that had full width. I also included a fake "logo" to demonstrate that I would want the to help the client feel like this was truly their next search experience. 

• I changed the order of the information to match existing search patterns for restaurants. For example, it is most common to give more hierachical importance to the location attribute. For this reason, I gave location a dark color while keeping the other attributes grey.

• I changed the h2 tags to be a darker version of the color given to me in the spec. This is because it is good UX practice not to have pure black on a site, and instead use a dark version of existing color. 

• I changed the order of tabs so that search results were on the left and categories on the right. I did this so that when the screen was resized (it is responsive) the most important information (search) would still be there. 

1b)RELEVANCE 

• I allow the user to sort on location and name attributes. For Ranking, I sort on "star_ratings". Therefore, if a user types in "Oakland," they will be able to see a list of restaurants in Oakland sorted from most popular to least popular. 

• I changed the wording to "what or where would you like to eat?" to be a more friendly prompt to the user. 

2) LEGIBILITY & REUSABILITY 

I commented my code throughout. I wrote a script in Javascript to combine two JSON files into one. 

3) ATTENTION TO DETAILS 

I also implemented a Search bar using the Algolia Search tool. The search bar highlights when the user clicks into it. 


