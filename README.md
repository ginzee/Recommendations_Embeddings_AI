Recommendation engine created using OpenAI embeddings, including classification processes. 
Service imports "Review Text" from an e-commerce CSV.
Then proceeds to create embeddings for each review and store them in a vector DB.
In parallel, the service creates "topics" and embeds them. 
The service proceeds to categorize each "Review Text" to a certain "topic."
Finally, the service offers a function that recommends a number of reviews for each suggested topic.
The same function is then used to extract reviews most similar to a given review. 
Note this project's CSV file is unavailable as it was performed directly on an online course (DataCamp).
