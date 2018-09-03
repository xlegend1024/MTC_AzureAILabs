# Delivery guide
This is a hands-on instructor guided lab. As such the students' instructions don't include a comprehensive discussion of all concepts 
and technologies covered in the lab. It is expected that the instructor will walk students through the steps of the lab and while doing that 
deep dive into the key topics and answer questions as necessary.

The goal of this document is to provide the instructor with hints on what should be covered at each step of the lab.

## Audience
This lab targets developers who may not have an AI/ML background. If there are participants who are new to AI/ML, the instructor should introduce key AI, Machine Learning and Deep Learning concepts. The lab's parent repo (MTC_AzureAILabs) includes two teaching tools that instructors are free to use:
- A gentle introduction to AI/ML - this is the recommended tool for the lab's target audience
- AI/ML foundations - this is a more formal coverage of AI/ML topics and is recommended to support discussions with data scientists and professional AI developers


## Hints for each step of the lab
**Before you start the hands-on exercises**
- Introduce key Machine Learning and Deep Learning concepts (Optional)
- Introduce key computer vision tasks including:
  - image classification
  - object detection
  - object segmentation
- Introduce key computer vision applications. E.g.:
  - Autonomous vehicles
  - Quality assurance
  - Workplace safety
  - Medical imaging
  - Robotics
- Provide and overview of Azure AI services with the focus on Cognitive Services

**Step 1 - Environment Set Up**
- Briefly review Azure concepts that are relevant in the context of the lab. E.g.  Azure Subscription, Azure Access, Azure Portal, Azure CLI, Azure SDK, Azure Resource Groups, Azure Storage
- Describe different ways of provisionig Custom Vision Service, including Azure Portal and Custom Vision Service web GUI
- Review key components and capabilities of Custom Vision Service, including: 
  - types of models you can train
  - domains
  - Custom Vision Service workflow
  - web GUI
  - supported SDKs 
  - billing model
  - prediction points
  - exporting trained models.
- Provide a high level overview of what is happening behind the scenes: transfer learning


