# place2vec
This repository provides the ground truth for comparing Point-Of-Interest(POI) type similarity and relatedness. The ground truth data is collected using Amazon Mechanical Turk Human Intelligence Task. Two types of tasks are use:
1. Binary-based Task
This task asks 25 human judges to choose the most dissimilar place types from 3 candidate place types. For example, for the triplet (Dentist, Education, Orthodontist), the most dissimilar one many people would choose might be "Education", for the triplet (Fashion, Food, Shopping), many people might choose "Food" as the outlier. The final result is determined by the vote among 25 human judges.
2. Ranking-based Task
This task asks 25 human judges to rate the similarity from a scale of 1-7 between two place types. Assessment interface is specifically designed to adjust for the characteristics that human judgments of similarity are non-symmetric. 
