# FuzzyWuzzy Matching

## About The Project

### Context
Given that you are running an e-commerce platform, countering initiatives at a product level against a competitor would involve identifying and mapping the competitor's catalog of products against your own internal catalog before price comparisons are possible. This project aims to optimize the latter part - mapping stage - however automating this mapping process with 100% accuracy is impossible, hence a 2-stage mapping process is required - automated mapping in stage 1 followed by manual mapping in stage 2, to achieve 100% accuracy. Therefore, the primary goal is to decrease the no. of hours for manual mapping by increasing the accuracy and speed of automated mapping.

Utilized FuzzyWuzzy matching logic to map products between Shopee and Lazada for countering initiatives.

### Achievement
Successfully applied Token Sort and Token Set methods from FuzzyWuzzy python package for mapping product names and descriptions. Each product will have a total score of 400.

![product_matching_total_score](https://user-images.githubusercontent.com/24253921/131311805-6562c08a-e130-4c0b-b573-0158302651b7.jpg)

New FuzzyWuzzy logic increased accuracy by 16% by applying both Token Sort and Token Set methods from FuzzyWuzzy python package, and matched both product name and product description variables.

## Steps to Reproduce
