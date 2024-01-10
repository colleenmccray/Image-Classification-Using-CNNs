# Computer Vision: Plant Seedlings Classification

## Problem Statement

### Context
The agricultural industry, despite numerous technological advancements, still requires substantial manual effort for tasks such as sorting and recognizing different plants and weeds. This project addresses the need for modernization in agriculture by leveraging Artificial Intelligence (AI) and Deep Learning to automate the identification of plant seedlings. The integration of AI aims to significantly reduce the time and energy traditionally spent on manual identification, leading to improved crop yields, freeing up human involvement for higher-order decision-making, and promoting sustainable environmental practices in agriculture.

#### Objective

The primary objective of this project is to build a Convolutional Neural Network (CNN) capable of classifying plant seedlings into their respective categories. By utilizing deep learning techniques, the project aims to enhance efficiency and accuracy in identifying plant species, contributing to the automation of agricultural processes.

#### Data Dictionary

The dataset, provided by the Aarhus University Signal Processing group in collaboration with the University of Southern Denmark, includes images of unique plants from 12 different species. To facilitate seamless data/project handling, the images are stored in the images.npy file, and corresponding labels are available in Labels.csv.

#### **List of Species**
1. Black-grass
2. Charlock
3. Cleavers
4. Common Chickweed
5. Common Wheat
6. Fat Hen
7. Loose Silky-bent
8. Maize
9. Scentless Mayweed
10. Shepherds Purse
11. Small-flowered Cranesbill
12. Sugar beet

### Actionable Insights and Business Recommendations

Based on the analysis of Model 10, there are identified false positives primarily in classes 4 (Common Chickweed), 5 (Common Wheat), and 6 (Fat Hen). To improve the model's performance, the dataset can be balanced by increasing the available data points for the minority classes. This strategic adjustment is expected to enhance the model's accuracy and address the specific challenges observed in the mentioned classes.
