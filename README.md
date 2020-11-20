**Hello!**

Identification of different types of fonts contained in binary images using descriptors extracted separately and also with Histogram of Oriented Gradient (HOG).

it has purposes linked to academic research. Therefore, I was not allowed to leave the dataset available with this document.

**Here you'll find these descriptors/treatments:**

- Skeleton of Zhang-Suen;
- Histogram of Oriented Gradient (HOG);
- Image area;
- Image height and width;
- Contour area;
- Horizontal and vertical balancing;
- Image ratio;
- Compactness;
- Contour perimeter;
- Rectangle;
- Euler number;
- Area and perimeter of the convex closure;
- Convexity;
- Solidity.

**Also, I used two Machine Learning models to predict the new images:**

- K-means;
- Random Forest.

**Conclusions**

- Machine learning models applied with HOG performed much better than the ones with the descriptors extracted separately;
- The random forest performed better when compared to k-means, for both versions, with and without HOG;
- I used the Zhang-Suen skeleton because we have many fonts designed in a complex way. Thus, it was a good solution;
- I chose to work with skeletons to mitigate variations in the thickness of different sources.
