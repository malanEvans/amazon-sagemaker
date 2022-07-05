# Amazon SageMaker example1
## Train, Deploy and Evaluate a simple XGBoost model on Amazon SageMaker
In this example, it shows how to develop a machine learning model to predict whether a customer will enroll for a certificate of deposit.
This example is extracted from an Amazon SageMaker tutorial.
The dataset provided by AWS is used here (https://d1.awsstatic.com/tmt/build-train-deploy-machine-learning-model-sagemaker/bank_clean.27f01fbbdf43271788427f3682996ae29ceca05d.csv).
This example shows how to:
* Create a SageMaker notebook instance
* Prepare the data
* Train the model
* Deploy the model
* Evaluate model performance

### Create a SageMaker notebook instance
First of all, you must have an AWS account. If not, please sign up for an account to experience many services for free.

#### Step1
Sign in to the [Amazon SageMaker Console](https://console.aws.amazon.com/sagemaker/) and select your preferred AWS region. You can use the already selected AWS region.
AWS region is the infrastructure region where the cluster for this particular notebook instance is located.

#### Step2
Select Notebook Instances from left navigation pane to Create notebook instance.
