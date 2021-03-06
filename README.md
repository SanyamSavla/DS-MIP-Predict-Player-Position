<div align="center">
 
<h1 align="center">Predict Positions of Football Players ⚽</h1>
  
![INTRO](./introFifa.png)
  
[![](https://img.shields.io/badge/Made_with-R-blue?style=for-the-badge&logo=R)](https://www.r-project.org/)
[![](https://img.shields.io/badge/IDE-Visual_Studio_Code-purple?style=for-the-badge&logo=visual-studio-code)](https://code.visualstudio.com/  "Visual Studio Code")
</div>


<p align="center">
A football team normally consists of 11 players: one goalkeeper and ten outfielders who play defensive, midfield, and attacking positions. Goalkeepers, unlike other players on the pitch, do not change positions or occupy significant sections of the field. This system can suggest the optimum location for a plater in the team based on data from FIFA players and their performance metrics. In addition, we analyzed essential features of high business value to ensure the optimal administration of a club.
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#technologies-&-dataset">Tech & Dataset</a></li>
    <li><a href="#data-analysis">Data Analysis</a></li>
   <li><a href="#machine-learning">Machine Learning</a></li>
    <li><a href="#contact">Contact Us</a></li>
  </ol>
</details>

## Technologies & Dataset

* [R](https://www.r-project.org/)

* [Fifa Dataset](https://www.kaggle.com/thec03u5/fifa-18-demo-player-dataset)


<!-- Data Analysis -->

## Data Analysis

1. Finding Distribution and the Average of The Players in each League:

![1](./1.png)

2. Total Market Value in each League:

![2](./2.png)

3. Visualization of the Position:

![3](./3.png)

4.  Correlation between Finishing & Shot Power:

![4](./4.png)

5.  Contract Analysis:

![5](./5.png)

6.  Top 10 Wonderkids:


![6](./6.png)


## Machine Learning

1. Dimensionality Reduction using PCA:

![7](./7.png)

To explain 90% of the variance, we have to go up to the 8th component.

![8](./8.png)

General patterns are still visible. The first component clearly distinguishes goalkeepers from the rest of the players.

2. Dimensionality Reduction using t-SNE:

![9](./9.png)

t-SNE is a non-linear dimensionality reduction algorithm that seeks to finds patterns in the data by identifying clusters based on similarity of data points.

3. KNN Model:

![10](./10.png)

Accuracy was used to select the optimal model using the largest value.
The final value used for the model was k = 55.

4. Results on Test Data:

![11](./11.png)




<!-- CONTACT -->
## Contact

Shreyas  - shreyas.mm@somaiya.edu

Sanyam - sanyam.savla@somaiya.edu
