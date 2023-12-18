# Beer Recommender System

## Project Description
This project, a part of the Analytics for Unstructured Data course, develops a sophisticated recommender system for craft beers. Utilizing user-generated reviews from [BeerAdvocate](https://www.beeradvocate.com), the system identifies user preferences in beer attributes and provides tailored recommendations. The approach involves extensive data scraping, natural language processing (NLP), sentiment analysis, and machine learning to process and analyze beer reviews.

## Installation
To run this project, you'll need Python 3.x and the following libraries:
- NumPy: For numerical operations.
- pandas: For data manipulation and analysis.
- NLTK (Natural Language Toolkit): For text processing and sentiment analysis.
- scikit-learn: For feature extraction and similarity computation.
- Selenium: For web scraping.

Clone the repository and install dependencies using:
```bash
git clone [repo-link]
pip install -r requirements.txt
```

## Usage
1. **Data Collection:** Run the web scraping script to collect beer reviews from BeerAdvocate.
2. **Data Processing:** Execute the data cleaning and preprocessing scripts to prepare the dataset for analysis.
3. **User Input:** Input desired beer attributes.
4. **Recommendation Generation:** Run the recommender system script to receive the top 3 beer recommendations based on input.

## Features
- **Web Scraping:** Employed Selenium for dynamic web scraping to extract 5-6k reviews of the top 250 beers from BeerAdvocate.
- **Data Cleaning:** Implemented techniques for handling missing values, duplicates, and irrelevant information.
- **Natural Language Processing:** Utilized NLTK for tokenization, stopword removal, and other text preprocessing steps. 
- **Sentiment Analysis:** Used NLTK's SentimentIntensityAnalyzer to determine the sentiment of each review.
- **Feature Extraction:** Extracted features from text data using CountVectorizer for further analysis.
- **Cosine Similarity:** Calculated cosine similarity between user preferences and beer attributes to generate recommendations.
- **Machine Learning Concepts:** Explored and applied basic machine learning techniques for pattern recognition and recommendation.

## System Workflow
1. **Data Acquisition:** Extraction of beer reviews.
2. **Data Preprocessing:** Cleaning and preparing data for analysis.
3. **Feature Engineering:** Transforming text data into a suitable format for machine learning algorithms.
4. **Model Building:** Developing the recommendation algorithm based on cosine similarity.
5. **User Interaction:** Interface for receiving user preferences and displaying recommendations.

## Contributing
Contributions to this project are welcome. Please adhere to the following guidelines:
- Fork the repository.
- Create a new branch for your feature.
- Submit a pull request with a clear description of your changes.

## License
This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgements
Special thanks to the course instructors and my peers for their invaluable input and support throughout this project.

---

**Additional Note:** Ensure that all the links (like the repository link and license link) are correctly set. You might also want to add more specific instructions or examples under each section for clarity. This README provides a detailed overview of your project, making it easier for others to understand and contribute to your work.
