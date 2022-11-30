
### How did I choose my K value?
Ref: <a href = "https://medium.com/analytics-vidhya/how-to-determine-the-optimal-k-for-k-means-708505d204eb"> method for finding optimal k </a>
- Calculated all the WSS errors and their corresponding k values and stored it in dictionary and then choose the k for which there is a sharp turn (**Elbow method**). <br><br>
![elbow](https://user-images.githubusercontent.com/75074904/204827576-f1f1cdee-6f26-4f3b-a951-df20a0af63b5.png)
<i>Img1: image showing plot from elbow method </i><br><br>
- Stored nearest descriptor’s index in ```nearest_features.txt```, so to visualize key points, we can access image number and it’s corresponding key point and descriptor for visualization.

### Scope of improvement
- [ ] use TF-IDF for histogram matching
- [ ] instead of randomly intializing cluster-centroids, use K-means++ algorithm.

### Flowchart
![Blank diagram](https://user-images.githubusercontent.com/75074904/204826175-3fe5a001-57d5-4d3d-81f9-5cdfb7ea623e.png)
<i>Img2: Flowchart of process flow. </i>
