# facemasq-model
facemasq-model

# Model Goals for the FaceMasq App
-face detection
-facemasq generation
-facemasqing photo
-facemasqing video

# Amazon Sagemaker Notes

Sagemaker is for creating and managing neural network models

## typical workflow
1. Generate Example Data (done in Jupyter Notebook)
    a. Fetch (from storage or online)
    b. Clean (standardize data)
    c. Prepare (data transformations to improve data for model training)
2. Train Model
   a. Train 
   b. Evaluate 
3. Deploy Model 
    a. Deploy to Prod
    b. Monitor and Collect Data