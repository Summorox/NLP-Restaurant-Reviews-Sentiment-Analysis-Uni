# Foodriven
## Overview
This repository contains a group project developed as part of a master's program in Artificial Intelligence at ISEP, completed in 2023. This experimental project was developed to explore the use of natural language processing (NLP) techniques to analyze restaurant reviews, identifying keywords associated with positive and negative sentiments, aiming to help restaurant managers understand customer feedback better by highlighting aspects that customers love or dislike.

## Methodology
1. **Data Collection**: Reviews were taken from Yelp's academic dataset (https://www.yelp.com/dataset).

2. **Sentiment Analysis**: A custom LSTM network, using word embeddings, is trained to classify sentiment as positive or negative. FastText embeddings are also used to capture word similarities to help relate the content of the reviews to specific aspects like "service" or "food."

3. **Topic Modeling**: LDA (Latent Dirichlet Allocation) is used to extract high-frequency topics within each sentiment category, to highlight prominent themes and patterns.

## Members
| Name | Institutional Email | 
|-----------------|-----------------|
| Jorge Felício    | 1181244@isep.ipp.pt    | 
| Alessandro Cunha    | 1220183@isep.ipp.pt    | 
| Gabriel Ribeiro    | 1220189@isep.ipp.pt    | 
| Heloisa Guimarães | 1222616@isep.ipp.pt |

## Usage
1. Open and execute `Foodriven.ipynb` in a Jupyter environment or in Google Colab.
2. Follow the steps described in the file to preprocess the data, train the model, analyze sentiment, and extract keywords.

The file assumes that you have yelp's dataset saved on your google drive, but you can alter the path or import it locally.
