# Cluster analysis of reader engagement
This code generates the results presented in the paper "Application of cluster analysis to identify different reader groups through their engagement with a digital reading supplement", encompassing all tables, figures, as well as detailed results in the appendices and supplementary materials.

Key points
-
* 6 indicator of engagements: all hours spent, variety of games played, all attempts, the number of levels played, days of playing, proportion of early exit rounds
* 4 indicators of performance: number of levels mastered, time to mastery, attempts to mastery, speed to mastery
* 5 clustering algorithms: Gaussian mixture models, k-means, k-medoids (partition around medoids), clustering large applications, hierarchical clustering
* Radar charts of visualizing complex and high dimensional results

Overview
-
* We utilized the log file dataset to create 6 indicators of engagement data for each user.
* We applied 5 popular clustering algorithms to the engagement data.
* Determined the best performing clustering results based on clustering validation.
* Visualized the clustering results.
* Explored the association between engagement and 4 indicators of performance.
* In relation of the engagement for each cluster with their initial literacy ability.
* Visulized the engagement and performance using radar charts for each cluster.


## Table of contents of the code provided (refer to the paper)
1.  Load packages needed
2.  Data pre-processing to create the engagement data from the log file dataset
3.  Apply five clustering algorithms to the engagement data (including figure 2 - number of clusters; figure 3 - clustering results)
4.  Validation metrics to evaluate algorithms (including Table 1 - validation results)
5.  K-means clustering results (including Figure 4 - Initial literacy ability for each cluster; Figure 5&6 - radar charts; Table S.6 & S.7 for average values of engagement/performance for each cluster)
6. Exploratory data analysis - Figure S.8 & S.9 usage of Clusters 3,4, and 7 across levels of two skills

Abstract of the paper
-
*The focus of this study is the identification of reader profiles that differ in performance and progression in an educational literacy app. A total of 19,830 students in Grade 2 from 347 Elementary schools located in 30 different districts in the United States played the app from 2020 to 2021. Our aim was to identify unique groups of readers using an unsupervised statistical learning technique - cluster analysis. Six indicators generated from the students’ log files were included to provide insights into engagement and learning across four different reading-related skills: phonological awareness, early decoding, vocabulary, and comprehension processes. A key aim was to evaluate the implementation and performance of Gaussian mixture models, k-means, k-medoids, clustering large applications and hierarchical clustering, alongside provision of detailed guidance that can benefit researchers in the field. K-means algorithm performed the best and identified nine groups of readers. Children with low initial reading ability showed greater engagement with code-related games (phonological awareness, early decoding) and took longer to master these games, whereas children with higher initial ability showed more engagement with meaning-related games (vocabulary, comprehension processes). Our findings can inform further research that aims to understand individual differences in learning behaviour within digital environments both over time and across various cohorts of children.*
