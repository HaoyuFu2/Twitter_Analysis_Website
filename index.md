---
layout: default
---

## Team Members

- **Haoyu Fu**  
  Email: [h6fu@ucsd.edu](mailto:h6fu@ucsd.edu)
- **Yixuan Zhang**  
  Email: [yiz119@ucsd.edu](mailto:yiz119@ucsd.edu)


## Mentor

- **Haojian Jin**  
  Email: [haojian@ucsd.edu](mailto:haojian@ucsd.edu)




# Background

- **Traditional Polling**: Traditional methods include surveying, phone calling, and interviewing. These methods are time-consuming and require significant human resources.

- **Innovative Approach**: Our project seeks to explore novel methodologies for determining people's political affiliations using machine learning and large language models. This approach aims to potentially reduce the costs and resources needed for polling.

# Data

- **Data Source**: We utilize a Twitter dataset from Kaggle, which contains tweets tagged with #Biden and #Trump.

- **Data Format**: The cleaned data features include user IDs, tweet posting times, and the text content of tweets.

- **Pre-Processing**: We removed unnecessary information such as URL links, @ mentions, and hashtags to clean the tweet data.

# Methods

### Text Processing

- **Fine Tuning and Semantic Embedding**: We fine-tuned large language models (LLMs) with the tweet texts and prompted the LLMs to respond to questions on political topics. The responses were then converted into semantic embeddings for subsequent analysis.

- **Sentiment Clustering**: A sentiment analysis was performed on the tweet text to gauge users' emotions regarding the discussed topics. We then clustered the processed data to group users with similar sentiments together.

### Layers:
- With the text data processed, we fed the embeddings to dense layers, along with the
user ID and the post times, to generate a binary results showing whether the user
agree or disagree with a given political event or topic.

- **Dense layer** is a type of neural network tool, and our purpose of using dense layers is to capture the latent patterns within the embeddings.

# Results
TODO
TODO
TODO

# References
Junsol Kim and Byungkyu Lee. Ai-augmented surveys: Leveraging large language models and surveys for opinion prediction, 2023.
