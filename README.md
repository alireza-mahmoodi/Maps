# Maps

In this project I create a Voronoi diagram visualization of restaurant ratings using machine learning and the Yelp academic dataset. In the visualization, the segmented area contains multiple region, where each region is shaded by the predicted rating of the closest restaurant - yellow is 5 stars, blue is 1 star. Each dot in the map, represents a restaurant. The color of the dot is determined by the restaurant's location.


# Code in Action

This section visually depicts the final results of implementation.


## Unsupervised Learning

The following shows the implementation of k-means algorithm to find closest restaurants to each other. I set k=8 for visualization.

![](visual_demonstration/unsupervised.gif)


## Supervised Learning

The following shows the implementation of least-squares linear regression to predict user's ratings on the restaurants he hasn't visited before. The prediction is based on the restaurants that the user has visited before. The ratings are the numbers inside parenthesis over each colored dot.

![](visual_demonstration/supervised.gif)
