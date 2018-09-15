# forest_cover
The Jupyter notebook contains code to predict forest cover type for 30 x 30 meter cells within Roosevelt National Forest. There are seven forest cover types. Features used to predict forest cover type include qualitative variables such as soil type, as well as quantitative variables such as elevation. I also generated some new variables (e.g. diagonal distance to hydrology) based on existing variables (e.g. horizontal distance to hydrology and vertical distance to hydrology), so that the predictive accuracy of the models may improve.

To solve the multiclass prediction problem, I explored the use of three models: random forest, multilayer perceptron, and xgboost. Cross-validation accuracy of the random forest was about 79%, which was higher than that of the multilayer perceptron and xgboost (about 70%).

The data was provided by Jock A. Blackard and Colorado State University, and downloaded from the following Kaggle competition page: https://www.kaggle.com/c/forest-cover-type-kernels-only/data
