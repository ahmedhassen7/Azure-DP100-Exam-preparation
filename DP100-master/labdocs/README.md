# DP-100: Designing and Implementing a Data Science Solution on Azure

> ## Important Notice!
>
> This repo will be replaced by a [new repo](https://aka.ms/mslearn-dp100) on **December 12th 2020**. The corresponding courseware will also be updated at this time. We're making this change to:
> - Consolidate the labs used in the [DP-100 instructor-led course](https://docs.microsoft.com/learn/certifications/courses/dp-100t01_) and the self-paced exercises in the equivalent online modules on [Microsoft Learn](https://docs.microsoft.com/learn/paths/build-ai-solutions-with-azure-ml-service/).
> - Update labs to reflect recent changes in the Azure Machine Learning service and SDK.
> - Add new labs on topics related to responsible machine learning.
>
> On Dec 7th 2020, Azure ML SDK 1.19.0 was released. In this release, estimators are deprecated; so any labs that use estimators will fail. We'll be releasing a refreshed version of the course next week, which will address this (and other) issues. In the meantime, you can apply either of the following workarounds:
> - Pin the SDK version to 1.18.0 (so in steps to install the SDK, use pip install azureml-sdk==1.18.0. However, you might experience some compatibility issues in later labs)
> - Use the updated labs (which will be the "official" labs for the refreshed course from next week onwards) at https://aka.ms/mslearn-dp100 - they more or less follow the same flow as the existing labs, but do not use estimators.
>
> After a short interval, this repo will be archived.

## Course Labs

Welcome to the hands-on lab exercises for course [DP-100 *Designing and Implementing a Data Science Solution on Azure*](https://docs.microsoft.com/en-us/learn/certifications/courses/dp-100t01). The labs are designed to accompany the course and enable you to practice using the technologies described in the classroom materials.

You should complete the labs in order, following the instructions in each Markdown document carefully.

The labs require a Microsoft Azure subscription. If your instructor has not provided you with one, you can sign up for a free trial at [https://azure.microsoft.com](https://azure.microsoft.com).

> **Tip**: As you work through the labs, you may experience unexpected issues due to idiosyncratic browser settings, network configurations, and so on. We've documented a few common issues in the [Tips](TIPS.md) document that may help. You can also view [known issues](https://github.com/MicrosoftLearning/DP100/issues) for these labs.

### Module 1: Introduction to Azure Machine Learning

- [Lab 1A: Creating an Azure Machine Learning Workspace](Lab01A.md)
- [Lab 1B: Working with Azure Machine Learning Tools](Lab01B.md)

### Module 2: "No-code" Machine Learning with Designer

- [Lab 2A: Creating a Training Pipeline with the Azure ML Designer](Lab02A.md)
- [Lab 2B: Deploying a Service with the Azure ML Designer](Lab02B.md)

### Module 3: Running Experiments and Training Models

- [Lab 3A: Running Experiments](Lab03A.md)
- [Lab 3B: Training and Registering Models](Lab03B.md)

### Module 4: Working with Data

- [Lab 4A: Working with Datastores](Lab04A.md)
- [Lab 4B: Working with Datasets](Lab04B.md)

### Module 5: Compute Contexts

- [Lab 5A: Working with Environments](Lab05A.md)
- [Lab 5B: Working with Compute Targets](Lab05B.md)

### Module 6: Orchestrating Operations with Pipelines

- [Lab 6A: Creating a Pipeline](Lab06A.md)
- [Lab 6B: Publishing a Pipeline](Lab06B.md)

### Module 7: Deploying and Consuming Models

- [Lab 7A: Creating a Real-time Inferencing Service](Lab07A.md)
- [Lab 7B: Creating a Batch Inferencing Service](Lab07B.md)

### Module 8: Training Optimal Models

- [Lab 8A: Tuning Hyperparameters](Lab08A.md)
- [Lab 8B: Using Automated Machine Learning](Lab08B.md)

### Module 9: Interpreting Models

- [Lab 9A: Reviewing Automated Machine Learning Explanations](Lab09A.md)
- [Lab 9B: Interpreting Models](Lab09B.md)

### Module 10: Monitoring Models

- [Lab 10A: Monitoring a Model with Application Insights](Lab10A.md)
- [Lab 10B: Monitoring Data Drift](Lab10B.md)

> **Important**: Remember to stop any virtual machines used in these labs when you no longer need them - this will minimize the Azure credit incurred for these services. When you have completed all of the labs, consider deleting the resource group you created if you don't plan to experiment with it any further.

## Contributions

At this time, we are not accepting external contributions to this repo. If you have suggestions or spot any errors, please report them as [issues](https://github.com/MicrosoftLearning/DP100/issues).

