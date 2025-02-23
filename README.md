# Content-Based Movie Recommendation System Overview

This project implements a content-based recommendation system that suggests movies based on a user's text input. The system utilizes TF-IDF vectorization and cosine similarity to compare user input against a dataset of movie titles, returning the most relevant recommendations.

## Example Use Case
User Input: "Reference Title"
System Output: The top 3 most similar movies based on text similarity.

## Dataset
The dataset used is Movies.csv, containing movie titles. The dataset should have a column title representing the movie titles.

## Installation & Setup

### Prerequisites
Ensure you have Python 3.9.6 installed along with the necessary dependencies:

### Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib

## Running the Recommendation System
Run the Python script by executing:

### Example Run
When prompted, enter a reference from the data and the number of recommendations:
### Example Output
Recommending movies similar to Romance...
Recommended: True Romance (score: 0.7350365307989193)
Recommended: Murphy's Romance (score: 0.677540543893483)
Recommended: Office Romance (score: 0.677540543893483)

## Code Structure
The project consists of:
- recommend.py: Main script implementing TF-IDF vectorization and cosine similarity.
- Movies.csv: The dataset file.
- requirements.txt: List of dependencies.
- README.md: This documentation.

## Algorithm Steps
1. Load the dataset: Read Movies.csv into a Pandas DataFrame.
2. Preprocess Data: Strip whitespace from movie titles.
3. Vectorize Titles: Use TF-IDF vectorization to convert movie titles into numerical vectors.
4. Compute Similarity: Calculate cosine similarity between movie titles.
5. Return Recommendations: Sort and return the top N most similar movies.

## Expected Results
When given an input movie title, the system should return N relevant movie titles based on text similarity.

## Salary expectation - 6000$/month 
## Demo
A brief screen recording showcasing the recommendation system can be found here https://drive.google.com/file/d/1OO_sTSmVf7hGjKF0wer-JjXNaZi-L9V1/view?usp=sharing.
