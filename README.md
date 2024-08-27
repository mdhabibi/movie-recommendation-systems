# Movie Recommendation Systems

<div align="center">
  <img src="images/poster.png" width="400">
</div>

## Overview

This repository contains a comprehensive collection of movie recommendation systems. The goal is to implement and explore various methods of recommending movies to users, including:

- **Collaborative Filtering:** Based on user-item interactions.
- **Content-Based Filtering:** Based on movie metadata (e.g., genre, cast, overview).
- **Bayesian Average:** Combines multiple factors like user ratings and popularity.
- **Future Methods:** Planned additions include hybrid models, matrix factorization, deep learning-based recommenders, and more.

## Table of Contents

- [Overview](#overview)
- [Implemented Methods](#implemented-methods)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Implemented Methods

1. **Collaborative Filtering**
   - Uses user behavior (ratings) to recommend movies that similar users have liked.
   - Example: User-based and Item-based collaborative filtering.

2. **Content-Based Filtering**
   - Recommends movies similar to those the user has liked in the past, based on metadata.
   - Example: TF-IDF vectorization, cosine similarity.

3. **Bayesian Method**
   - A simple yet effective approach combining various factors such as average rating and popularity.
   - Example: IMDB-style weighted rating.

## Usage

To explore the recommendation systems:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-systems.git
   cd movie-recommendation-systems
