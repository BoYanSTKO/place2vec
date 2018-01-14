# Place2Vec
This repository provides the ground truth for comparing Point-Of-Interest(POI) type similarity and relatedness. The [ground truth data](https://github.com/BoYanSTKO/place2vec/blob/master/HIT.zip) is collected using Amazon Mechanical Turk Human Intelligence Task. Two types of tasks are use:
1. Binary-based Task

   This task asks 25 human judges to choose the most dissimilar place types from 3 candidate place types. For example, for the triplet (Dentist, Education, Orthodontist), the most dissimilar one many people would choose might be "Education", for the triplet (Fashion, Food, Shopping), many people might choose "Food" as the outlier. The final result is determined by the vote among 25 human judges.

2. Ranking-based Task

   This task asks 25 human judges to rate the similarity from a scale of 1-7 between two place types. Assessment interface is specifically designed to adjust for the characteristics that human judgments of similarity are non-symmetric. 

This [ground truth data](https://github.com/BoYanSTKO/place2vec/blob/master/HIT.zip) can be used as baselines to evaluate models for POI type similarity measurements. If you use this dataset in your work, please kindly cite the paper in the reference section. Download [here](https://github.com/BoYanSTKO/place2vec/blob/master/HIT.zip).

## Reference
Bo Yan, Krzysztof Janowicz, Gengchen Mai, and Song Gao. 2017. [From ITDL to Place2Vec – Reasoning About Place Type Similarity and Relatedness by Learning Embeddings From Augmented Spatial Contexts](https://geog.ucsb.edu/~jano/place2vec.pdf). In Proceedings of SIGSPATIAL’17, Los Angeles Area, CA, USA, November 7–10, 2017, 10 pages. https://doi.org/10.1145/3139958.3140054

```
@inproceedings{Yan:2017:IPR:3139958.3140054,
 author = {Yan, Bo and Janowicz, Krzysztof and Mai, Gengchen and Gao, Song},
 title = {From ITDL to Place2Vec: Reasoning About Place Type Similarity and Relatedness by Learning Embeddings From Augmented Spatial Contexts},
 booktitle = {Proceedings of the 25th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems},
 series = {SIGSPATIAL'17},
 year = {2017},
 isbn = {978-1-4503-5490-5},
 location = {Redondo Beach, CA, USA},
 pages = {35:1--35:10},
 articleno = {35},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/3139958.3140054},
 doi = {10.1145/3139958.3140054},
 acmid = {3140054},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {Geo-Semantics, Machine Learning, Points of Interest, Similarity},
}
```
