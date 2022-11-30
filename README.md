
### How did I choose my K value?
Ref: <a href = "https://medium.com/analytics-vidhya/how-to-determine-the-optimal-k-for-k-means-708505d204eb"> method for finding optimal k </a>
- Calculated all the WSS errors and their corresponding k values and stored it in dictionary and then choose the k for which there is a sharp turn (**Elbow method**).
- Stored nearest descriptor’s index in ```nearest_features.txt```, so to visualize key points, we can access image number and it’s corresponding key point and descriptor for visualization.

### Flowchart
![Blank diagram](https://user-images.githubusercontent.com/75074904/204826175-3fe5a001-57d5-4d3d-81f9-5cdfb7ea623e.png)

### Results
![1051](https://user-images.githubusercontent.com/75074904/204826238-e390b4dd-d35a-4d9c-a113-b533857b560c.png)
