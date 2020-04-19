# Collaborative-Filtering-on-movies

User based collaborative filtering is used to recommend new movies to the target user.

Pearson Correlation Coefficient is used to measure the similarity of the target user with others. This similarity matrix when multiplied with the ratings gives the weighted rating matrix, which is the target users neighbors opinions about the movies for recommendation. The recommendation matrix is formed by dividing the sum of weighted rating matrix by the sum of the weights from the similarity matrix. This recommendation matrix is the target user's possible rating for the unwatched movies if he were to watch them.
