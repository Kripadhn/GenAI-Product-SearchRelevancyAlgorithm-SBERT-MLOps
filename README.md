# GenAI-Product-SearchRelevancyAlgorithm-SBERT-MLOps
<H2><B> Title </B></H2> Build Search Relevancy Algorithm with SBERT &amp; MLOps

<H2><B> Description </B></H2> This project aims to improve the search experience for news articles by leveraging the
Sentence-BERT (SBERT) model and the ANNOY approximate nearest neighbor library.
The project will be deployed on AWS using Docker containers and exposed as a Flask
API, allowing users to query and retrieve relevant news articles easily.

<H2><B> Approach </B></H2>
● Data Preprocessing:
<br>
○ Clean and preprocess the news article dataset, including tokenization,
removal of stop words, and normalization.
<br>
● SBERT Training:
<br>
○ Train the Sentence-BERT (SBERT) model using the preprocessed news
articles to generate semantically meaningful sentence embeddings.
<br>
● ANNOY Indexing:
<br>
○ Utilize the ANNOY library to create an index of the SBERT embeddings,
enabling fast and efficient approximate nearest neighbor search.
<br>
● Deployment on AWS with Docker:
<br>
○ Containerize the project components, including the Flask API, SBERT
model, and ANNOY index, using Docker.
<br>
○ Deploy the Docker containers on AWS EC2 Instance.
<br>

# Code Structure
![image](https://github.com/user-attachments/assets/851f664d-8595-4f31-8b90-56b343cee12c)

