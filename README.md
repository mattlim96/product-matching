# FuzzyWuzzy Matching

## About The Project

### Context
Given that you are running an e-commerce platform, countering initiatives at a product level against a competitor would involve identifying and matching the competitor's catalog of products against your own internal catalog before price comparisons are possible. This project aims to optimize the latter part - matching stage - however automating this matching process with 100% accuracy is impossible, hence a 2-stage matching process is required - automated matching in stage 1 followed by manual matching in stage 2, to achieve 100% accuracy. Therefore, the primary goal is to decrease the no. of hours for manual matching by increasing the accuracy and speed of automated matching.

### Methodology
1. Compile product names and descriptions from each seller into a dictionary.
2. Iterate through list of sellers then apply Token Sort and Token Set method to match product names and descriptions. (Note: Each product will have a total score of 400.)
3. Extract only the highest score for each product matching.

Example Output:
![product_matching_total_score](https://user-images.githubusercontent.com/24253921/131312205-81bcd547-a2f6-4173-a44a-febf9dd89847.jpg)

### Achievement
Successfully developed a more accurate matching methodology by applying both Token Sort and Token Set methods from FuzzyWuzzy python package for matching product names and descriptions. The old methodology only applied Token Sort and did not match product descriptions.
