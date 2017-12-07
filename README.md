# Java GUI for Yelp business dataset with MongoDB backend 

Goal:
Create application to run queries on the MongoDB NoSQL database on Yelp.com’s
business review dataset.

Project Description:
The goal of the project is to to run queries from Yelp’s business review data on the
MongoDB NoSQL database. We will then provide users with a UI that can run and
discover different attributes and categories associated with each business. The
application will then allow users to search businesses through the various categories
the user wants to have. Some search results may include points of interest and
proximity using the spatial features of MongoDB. The application should also allow
users to view any review provided at the particular businesses.

Dataset Description:
The Yelp dataset includes businesses, reviews, user data and even check-in and tips
paid. It includes 4,700,000 reviews, 156,000 businesses, 200,000 pictures, and 12
metropolitan areas. There are various different business attributes for each business,
such as hours, parking, availability, and ambience. The data is available in both JSON
and SQL files. The dataset has five json files.
  
  - Business.json contains business data including location data, attributes, and
  categories.
  - Review.json contains full review text data including the user_id that wrote the
  review and the business_id the review is written for.
  - User.json includes user data including the user's friend mapping and all the
  metadata associated with the user.
  - Checkin.json has check-ins on a business.
  - Tip.json contains tips written by a user on a business.

Plan:
  - Importing the Yelp Business Review dataset to MongoDB.
  - Developing queries to search the database.
  - Establishing connectivity with the MongoDB.
  - Embedding/executing queries in/from the code. Retrieving query results and parsing
    the returned results to generate the output that will be displayed on the GUI.
  - Implementing a GUI on Java where the user can, browse through main and
    sub-categories for the businesses; select the business categories that
    user wants to search for.
  - Establishing connectivity with the MongoDB.

Queries in the application will allow users to
  - Search for the businesses that belong to the main categories that user specifies
    along with checkin/review information (Fig 1).
  - Search for users have either all the specified attributes or that have any of the
    attributes specified.
  - Select a certain business in the search results and list all the reviews for that
    business.
  - Select a user in the search results and list all the reviews for that user.
  - Filter out the search results by point of interest and proximity. The point of
    interest drop down must include 5 addresses of your choice as point of interests.
    The proximity drop down must include the following: “5 miles”, “10 miles”, “20
    miles”, “30 miles”, “50 miles”.
  - Select a certain business in the search results and list all the reviews for that
    business.
<p align="center">
  <img width="667" height="549" src="https://raw.githubusercontent.com/TejasShahpuri/Yelp-on-MongoDB/master/Pics/Screenshot.png">
</p>

Class project for DS220: Data Management for Data Sciences
The Pennsylvania State University
