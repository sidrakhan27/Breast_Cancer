# Breast_Cancer
In this project, i explored the Breast Cancer dataset from the sklearn library. I began by visualizing the distribution of the target variable and the correlation between the features. And also looked at the distribution of mean radius by tumor type and created scatter plots of mean radius and mean texture by tumor type. Then plotted the box plot and violin plot of mean smoothness and worst area by tumor type.

Next, i used principal component analysis (PCA) to reduce the dataset into two components. One of the main reasons for using PCA is to reduce the dimensionality of the data when there are a large number of features or variables. In this case, the original dataset had 31 columns or features, which can be difficult to visualize and analyze effectively. By applying PCA, i was able to reduce the dataset to just two 
principal components that captured most of the variance in the data. This makes it much easier to visualize and interpret the data, as i can now plot the data points on a 2D scatter plot. Additionally, reducing the number of features also helps in reducing the computational complexity of machine learning algorithms and can improve their performance.and then applied logistic regression to predict the type of tumor. After training and testing the model, also achieved an accuracy of 97% and an AUC score of 0.997. This suggests that the model performs well in classifying tumors as either malignant or benign based on the features included in the dataset. Overall, this project demonstrates how exploratory data analysis and machine learning techniques can be applied to understand and classify breast cancer tumors.
