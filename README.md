# Hotel Recommender System

## Overview
This Hotel Recommender System uses natural language processing to analyze hotel reviews and recommend hotels based on textual similarity. The system processes and clusters reviews, allowing users to input their own review to receive hotel recommendations that closely match their preferences in terms of sentiment and content.

## Key Features
- **Text Preprocessing**: Cleans and prepares textual data for NLP operations.
- **Semantic Analysis**: Utilizes Sentence Transformers to generate semantically meaningful embeddings of hotel reviews.
- **Clustering**: Implements K-means clustering to group similar reviews, enhancing the recommendation process.
- **Similarity Comparison**: Uses cosine similarity to find the closest matching reviews within the same cluster, providing targeted hotel recommendations.
- **Web Interface**: Offers a user-friendly web interface built with Flask, where users can submit reviews and view recommended hotels alongside the reviews that most closely match their input.

## Demo Video
Watch this short demonstration of the system in action:
[![Demo Video](https://img.youtube.com/vi/M5F_n_GYDgg/0.jpg)](https://www.youtube.com/watch?v=M5F_n_GYDgg)

## Technologies Used
- Python 3
- Flask
- Pandas
- NumPy
- Sentence Transformers
- Scikit-Learn

## Setup and Installation
To get this project up and running on your local machine, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/hotel-recommender-system.git
   cd hotel-recommender-system
