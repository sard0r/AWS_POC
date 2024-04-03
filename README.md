# Host a YOLOv8 model on a SageMaker Endpoint
This aim of this project is to host a [YOLOv8](https://github.com/ultralytics/ultralytics)* PyTorch model on a [SageMaker Endpoint](https://aws.amazon.com/sagemaker/) and test it by invoking the endpoint. The project utilizes [AWS CloudFormation/CDK](https://aws.amazon.com/cloudformation/) to build the stack and once that is created, it uses the SageMaker notebooks created in order to create the endpoint and test it.

## AWS Architecture:
![AWSArchitecture](assets/AWSArchitecture.png)


