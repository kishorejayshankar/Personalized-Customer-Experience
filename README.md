# Personalized Product Recommendation
# Overview
### Problem
Recommending the right T-shirts to each customer can be challenging with a vast selection. Traditional recommendation systems may struggle to capture the nuances of individual preferences, leading to suboptimal suggestions and missed opportunities for sales.

### Solution
This Gen-AI project proposes a solution using Generative Adversarial Networks (GANs) to tackle this problem. By leveraging machine learning techniques, specifically GANs, we aim to provide personalized product recommendations for T-shirts based on each customers unique characteristics and preferences.

### Key Features
- **Data-driven Approach**: Utilize customer data, including purchase history, demographics (age, gender), and browsing behavior, to train the GAN model.
- **Synthetic Profile Generation**: Generate synthetic customer profiles representing new customer segments learned by the GAN.
- **Personalized Recommendations**: Tailor product recommendations for each user based on their synthetic profile, enabling personalized shopping experiences.

### Usage
Data Generation :
* Generate synthetic customer data using the provided generate customer data function.
* Save the generated data to a CSV file for training the GAN model.

GAN Training :
* Load the customer data from the CSV file.
* Preprocess the dataset, including normalization and feature engineering if necessary.
* Build and train the GAN model using the preprocessed customer data.

Recommendation System :
*Generate synthetic profiles using the trained GAN model.
*Cluster the synthetic profiles to identify customer segments.
*Implement recommendation algorithms to provide personalized product recommendations for each user.
