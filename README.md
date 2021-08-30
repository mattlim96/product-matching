# FuzzyWuzzy Matching

## About The Project

### Context
Given that you are running an e-commerce platform, countering initiatives at a product level against a competitor would involve identifying and mapping the competitor's catalog of products against your own internal catalog before price comparisons are possible. This project aims to optimize the latter part - mapping stage - however automating this mapping process with 100% accuracy is impossible, hence a 2-stage mapping process is required - automated mapping in stage 1 followed by manual mapping in stage 2, to achieve 100% accuracy. Therefore, the primary goal is to decrease the no. of hours for manual mapping by increasing the accuracy and speed of automated mapping.

### Methodology

#### Step 1

Each product will have a total score of 400, example shown in image below.
![product_matching_total_score](https://user-images.githubusercontent.com/24253921/131312205-81bcd547-a2f6-4173-a44a-febf9dd89847.jpg)

### Achievement
Successfully applied Token Sort and Token Set methods from FuzzyWuzzy python package for mapping product names and descriptions. 

New FuzzyWuzzy logic increased accuracy by 16% by applying both Token Sort and Token Set methods from FuzzyWuzzy python package, and matched both product name and product description variables.
