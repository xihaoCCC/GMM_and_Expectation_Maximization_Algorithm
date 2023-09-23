# Clustering Data with Gaussian Mixture Models via Expectation-Maximization Algorithm

## Summary
In this project, I started by generating three-dimensional synthetic data across three clusters, each following to a specified multivariate normal distribution. Then I 
fitted three Guassian Mixture Models (GMM) using Expectation-Maximization (EM) algorithm with 5, 12, 30 iterations. Lastly, I visualized and compared the clusters formed by each GMM iteration.


## Setup
This project is developed using Python 3 and Jupyter Notebook. Refer to `GMM_EM.ipynb` for the required packages.


## File Descriptions
- `GMM_EM.ipynb`: Python notebook responsible for data generation and model construction.
- `GMM_EM.pdf`: PDF export of the `GMM_EM.ipynb` notebook.
- `presentation.mp4`: A brief video presentation discussing the work and key concepts of the project.


## Content
This project includes 7 parts in total, specifically: 
1. Synthesize a multimodal Gaussian distribution
2. Fit a piecewise linear regression model
3. Fit three spline models with 2, 3, and 4 knots respectively
4. Compare the R-squared values and root mean square deviations (RMSD) of the models from the previous sections
5. Fit four polynomial models with degree 2,3,4,5 respectively
6. Compare the fitting times of the constructed models
7. Construct two polynomial models of degree 5 using Lasso and Ridge regularization techniques

### For inquiries or further discussion, please reach out to me at [xihaocao@163.com](mailto:xihaocao@163.com). Thank you!
