# Preprocessing: Sagemaker Image Classification
This repo contains the files for processing the input data to the necessary format for input into an Amazon Sagemaker Image Classification algorithm. 

The input data comes from the State Farm Distracted Driver Kaggle challenge, found here: [https://www.kaggle.com/c/state-farm-distracted-driver-detection](https://www.kaggle.com/c/state-farm-distracted-driver-detection). 

The images found in the Kaggle challenge are converted a training and validation inputs in RECORDIO file type. This is the preferred file structure for the Amazon Sagemaker Image Classification algorithm. The file conversion was completed by using the **im2rec.py** tool, provided by the MXNET project at Apache: [https://mxnet.apache.org/api/faq/recordio](https://mxnet.apache.org/api/faq/recordio).
