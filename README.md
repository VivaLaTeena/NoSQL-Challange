# NoSQL-Challange

Assignment Summary:

 I have been tasked with evaluating food hygiene ratings data from the UK Food Standards Agency for the food magazine "Eat Safe, Love." The assignment consists of three main parts:

Part 1: Database and Jupyter Notebook Set-Up

Import data from "establishments.json" into a MongoDB database named "uk_food" with a collection named "establishments."
Confirm database and collection creation.
Retrieve and display one document from the "establishments" collection.
Prepare the collection for use.
Part 2: Update the Database

Add a new halal restaurant, "Penang Flavours," with specific information to the database.
Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new restaurant with this BusinessTypeID.
Identify and remove establishments within the Dover Local Authority.
Convert certain string values to numbers using "update_many."
Part 3: Exploratory Analysis

Answer specific questions about the dataset for "Eat Safe, Love."
Questions include identifying establishments with hygiene scores equal to 20, establishments in London with a RatingValue of 4 or higher, the top 5 establishments with a RatingValue of 5 sorted by lowest hygiene score and proximity to "Penang Flavours," and the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.
The results are displayed using count_documents, pprint, and Pandas DataFrames as specified in each question
