# Searching for image by text query

Our dataset contains expert and crowdsourced evaluations of text-image correspondence.

Model should return as output the probability that the image matches the text, so the target variable should have values between 0 and 1.

It was adopted to solve the regression problem. The quality metric is RMSE.

## Resume 
- The pre-trained Inception v3 model was used for image vectorization
- The pre-trained DistilBert model was used for text vectorization
- The quality of work of two linear models LinearRegression and ElasticNet was checked.
- The quality of the neural network showed after 15 epochs of training seemed satisfactory, approximately 0.06 rmse.

## Skills and tools
- python
- pandas, numpy
- sklearn
- transformers
- pytorch
- DistilBertTokenizer
- Inception v3
