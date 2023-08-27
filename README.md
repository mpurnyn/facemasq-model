# facemasq-model
facemasq-model

# Model Goals for the FaceMasq App
-face detection
-facemasq generation
-facemasqing photo
-facemasqing video

# Amazon Sagemaker Notes

Sagemaker is for creating and managing neural network models

## Overview & Typical Workflow
[Sagemaker Overview](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works-mlconcepts.html)

1. Generate Example Data (done in Jupyter Notebook)
    a. Fetch (from storage or online)
    b. Clean (standardize data)
    c. Prepare (data transformations to improve data for model training)
2. Train Model
   a. Training Algorithm or Pre-Trained Model
        - [Sagemaker built in](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)
        - [SageMaker JumpStart](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-jumpstart.html)
   b. Evaluate 
        - using AWS SDK or Sagamaker Python Library
3. Deploy Model 
    a. Deploy to Prod
        - [Deploy models on Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/deploy-model.html)
    b. Monitor and Collect Data
        - ground truth