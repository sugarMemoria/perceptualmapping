# Perceptual Mapping based on Amazon Reviews

## Background
This project is designed to practice the perceptual mapping and multidimensional (MDS) plot learned in the Marketing Analytics course using R programming language. The main goal is to pick a product category and analyze the brands within that category and see if there are any insights to generate.

## Step Breakdown
1. Pick a brand based on personal preference/research need
2. Calculate the metric - cooccurrence
3. Calculate the metric - lift
4. Based on lift, build a dis-similarity matrix
5. Build MDS plot

## Tips and Roadblocks
1. There are different ways to calculate cooccurrence and lift; tread carefully
2. transform similarity matrix based on cooccurrence and lift to dissimilarity matrix because the MDS is based on dissimilarity
3. Interpretation of the MDS plot

## Sample Result
<img src="https://user-images.githubusercontent.com/33971367/110268821-526faa00-7f90-11eb-8679-79baff737c8b.png" width="672" height="480">

## Data Source
https://nijianmo.github.io/amazon/index.html

## Reference
*Justifying recommendations using distantly-labeled reviews and fined-grained aspects*
Jianmo Ni, Jiacheng Li, Julian McAuley
Empirical Methods in Natural Language Processing (EMNLP), 2019
