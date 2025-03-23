# Dimensionality-Reduction
Dimensionality Reduction is the process of removing the number of features in a dataset which makes the learning faster, simpler, and prevents overfitting to a certain extent.
## Step 1
### Normalization
The process of getting all the numerical features between the range of 0 and 1
We use MinMaxScaler() to fit and transform the values.
### Standardisation 
Getting the data to result in a Mean = 0 and Standard Deviation = 1. This is to make sure that the data follows a  normal distribution.
## Step 2 : Covalence matrix
### What is this matrix?
A covalence matrix is a symmetric square matrix that shows the correlation or relationships between two features.
- A positive covalence = features increase or decrease together
- A negative covalence = features are inversely proportional
- A null covalence = features are independent of each other
## Step 3 : Eigenvalues and Eigenvectors
- To find the important directions of variance in the data
- To transform data into a new coordinate system, Principal Components
- We sort these vectors by decreasing the eigenvalues because larger eigenvalues indicate a higher variance.
## Step 4 : PCA
- It is one of the techniques used for dimensionality reduction that transforms high-dimensional data into a lower-dimensional space.
- The principal Components are the new axes that are derived from the original dataset. They represent the directions of maximum variance in the data.
- PC1 = Captures the most variance in the data.
- PC2 = Captures the second most variance, orthogonal to PC1.
## Step 5 : Explained Variance
- It indicates the amount of variance from the he original dataset retained by each principal component.
- It helps determine the number of PC(s) required to capture most of the interpretable patterns in the data.
- Cumulative Variance:
    - To choose the smallest number of PCs that explain atleast 95% of the variance


