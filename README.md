# Electoral processes in the MSU Mech-Math student council

Collecting data and analyzing of electoral processes in the student council of Faculty of Mechanics and Mathematics of Lomonosov MSU. 

Libraries: numpy, pandas, BeautifulSoup4, requests, re, nltk, sklearn, scipy, matplolib


## Table of contents
- [Datasets](#datasets)
- [Machine learning approach](#machine-learning-approach)
- [The analysis](#the-analysis)


## Datasets

- The codes in [this folder](https://github.com/am-tropin/ssmm_database/tree/main/elections:%20source%20to%20library) collects the [library of datasets](https://github.com/am-tropin/ssmm_database/tree/main/library:%20main) about persons, elections, managements etc. 

- There are [dictionaries](https://github.com/am-tropin/ssmm_database/tree/main/dictionaries) about internal organization of the student council and the faculty that were filled manually.


## Machine learning approach

- The first problem was is clustering of all candidates. The given problem was solved by using **the scikit-learn K-means clustering**. The result is in the [person_clusters.csv](https://github.com/am-tropin/ssmm_database/blob/main/elections:%20ML/person_clusters.csv) file.

- The second problem was is clustering of all election programs. The given problem was solved by using **NLTK** for Russian language, manual grouping of mean-similar 2-grams and **the scikit-learn K-means clustering**. The result is in the [program_clusters.csv](https://github.com/am-tropin/ssmm_database/blob/main/elections:%20ML/program_clusters.csv) file.


## The analysis

- The processes were visualized using [Tableau Public](https://public.tableau.com/app/profile/aleksandr.tropin/viz/ElectoralProcessesinMSUMech-MathStudentCouncil/DB). 

- Dashboards were described in [Medium article](https://medium.com/@amtropin/project-electoral-processes-in-the-msu-mech-math-student-council-d5cdef293567). 

