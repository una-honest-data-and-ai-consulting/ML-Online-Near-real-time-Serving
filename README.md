# Online serving (near real-time)

Online inference is definitely more challenging than batch inference. Why? Due to the latency restrictions on our systems.

**Online inference** is about responding with a prediction to the request of the end user with a low latency.

**What to optimize**: latency

**End user**: usually interacts with a model directly available through an API

**Validation**: offline and online via A/B testing


---
## Where to start

Learn MLOps general concepts:
- [MLOps](https://ml-ops.org/)

Next learn how to build and run pipelines for online serving

on Azure cloud:
- [Orchestrate machine learning with pipelines on Azure](https://docs.microsoft.com/en-us/learn/modules/create-pipelines-in-aml/)
- [Create Azure Machine Learning Pipeline](https://github.com/MicrosoftLearning/mslearn-dp100/blob/main/08%20-%20Create%20a%20Pipeline.ipynb)
- [Deploy real-time machine learning services with Azure Machine Learning](https://docs.microsoft.com/en-us/learn/modules/register-and-deploy-model-with-amls/)
- [Create a real-time inferencing service on Azure](https://github.com/MicrosoftLearning/mslearn-dp100/blob/main/09%20-%20Create%20a%20Real-time%20Inferencing%20Service.ipynb)
- [Deploy a machine learning model to Azure Functions](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-functions)

on AWS:
- [Operationalizing machine learning pipeline on AWS](https://operational-machine-learning-pipeline.workshop.aws/)
- [Safe MLOps deployment pipeline on AWS](https://mlops-safe-deployment-pipeline.workshop.aws/)
- [AWS Lambda ML Model Deployment](https://github.com/schmidtbri/lambda-ml-model-deployment)

overall:
- [gRPC ML Model Deployment](https://github.com/schmidtbri/grpc-ml-model-deployment)

---
## Next step: Advanced workshop: Azure Online Serving (near real-time)
This workshop is WIP

It will cover a real-life use case of deploying a machine learning model to Azure Functions with Python runtime and its troubleshooting.

