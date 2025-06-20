# Content Based Movie Recommendation Systems

## Business Problem

## Project Overview

## Business Understanding
### Objective
To improve user satisfaction and engagement on a movie streaming platform by providing **Top 5 personalised movie recommendations** based on users' past ratings. The goal is to simulate how platforms like Netflix and Prime Video tailor suggestions to each user.

### Scope
This project uses the MovieLens `ml-latest-small` dataset. It focuses on:
- Explicit rating data (0.5 to 5.0 scale)
- Recommending unseen movies to users

### Success Criteria

| Metric                 | Goal                            |
|------------------------|----------------------------------|
| RMSE / MAE             | Below 1.0                        |
| Recommendation Relevance | Top 5 suggestions match user interests |
| Coverage               | Recommendations generated for most users |
| Scalability            | Can extend to larger datasets or real-world scenarios |

## Data Understanding

The dataset used is the `ml-latest-small` version from MovieLens, containing 100,836 ratings by 610 users across 9,742 movies.

### Key Files:
- `movies.csv` – Contains `movieId`, `title`, `genres`
- `ratings.csv` – Contains `userId`, `movieId`, `rating`, `timestamp`
- `tags.csv`  – Contains user-generated tags
- `links.csv`  – External references (IMDb, TMDb)

### Ratings Data:
- Ratings range from 0.5 to 5.0 in 0.5 increments
- Explicit feedback format
- 
## Modelling and Evaluation

## Conclusion
