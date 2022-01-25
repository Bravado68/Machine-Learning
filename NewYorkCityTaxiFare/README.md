
 <p align="center">
  <![image](https://user-images.githubusercontent.com/92938031/150936516-24cc0da2-340a-4318-a135-b24932f774a4.png)/>
</p>

 


Description
In this playground competition, hosted in partnership with Google Cloud and Coursera, you are tasked with predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations. While you can get a basic estimate based on just the distance between the two points, this will result in an RMSE of  5− 8, depending on the model used (see the starter code for an example of this approach in Kernels). Your challenge is to do better than this using Machine Learning techniques!

Evaluation Metric
The evaluation metric for this competition is the root mean-squared error or RMSE. RMSE measures the difference between the predictions of a model, and the corresponding ground truth. A large RMSE is equivalent to a large average error, so smaller values of RMSE are better. One nice property of RMSE is that the error is given in the units being measured, so you can tell very directly how incorrect the model might be on unseen data.

RMSE is given by:

where  𝑦𝑖  is the ith observation and

is the prediction for that observation.

Example 1. Suppose we have one observation, with an actual value of 12.5 and a prediction of 12.5 (good job!). The RMSE will be:

Example 2. We'll add another data point. Your prediction for the second data point is 11.0 and the actual value is 14.0. The RMSE will be:

Kernel Submissions

You can make submissions directly from Kaggle Kernels. By adding your teammates as collaborators on a kernel, you can share and edit code privately with them.

Submission File

For each key in the test set, you must predict a value for the fare_amount variable. The file should contain a header and have the following format:

Objectives
Determine the taxi fare given inputs using:

Tensorflow
PyTorch
Scikit Learn
