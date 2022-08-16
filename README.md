# Cloud Services

Main goal is to give students a sense of why they might need cloud services and, when they do, what their options are.
 
## Learning Goals

Learning goals listed at the top:

 - Explain the general concept of "the cloud";
 - Understand the cases where ***hardware acceleration*** is useful;
 - Understand the cases where ***cloud storage*** and the **Boto3** library in particular are useful;
 - Explain the purpose of ***deploying*** a machine learning model, particularly with the **Flask** library.

Summary at the end of the main lecture content:

* Cloud services are useful for **computationally intensive or long-running tasks**
* The major providers of cloud services are **Amazon Web Services (AWS), Microsoft Azure, and Google Cloud**
* As a data scientist, you will generally use cloud services to **get more computing power and/or to deploy machine learning models**
* If you want to get more computing power, consider:
  * Cloud instances/containers with GPUs, particularly **EC2**
  * Cloud notebooks, particularly **Google Colab**
  * Cloud storage, particularly S3 bucket storage with **Boto3**
* If you want to deploy a machine learning model, first pickle the model, then consider:
  * Deploying a model as an API, using either a **cloud function** or a minimal **Flask** app
  * Deploying a model as a full-stack web app, either using Flask or **Dash**

## Lecture Materials

[Jupyter Notebook: Cloud Services](cloud_services.ipynb)
