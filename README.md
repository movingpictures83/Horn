# Horn
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)
# Tested with: PluMA 1.0, R 3.2.5

PluMA plugin that computes dissimilarities using Horn's Overlap Index (Horn, 1966).
Thie plugin takes as input a CSV file where rows represent samples and columns represent community members,
with entry (i, j) indicating the abundance of member j in sample i.
It produces an output CSV file where rows and columns both represent samples, and entry (i, j) will then
be the level of dissimilarity between sample i and sample j.
