### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the submission code for the "ND9991 - C2 - Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

#### project-diagram.jpeg
AWS infrastructure diagram for the CloudFormation template.

#### project.yml
CloudFormation code YAML template for building the cloud infrastructure, as required for the project. 

#### project-parameters.json
JSON file for increasing the generic nature of the YAML code, contains parameter key-value pairs for the project. 

#### create.sh
Bash shell script utility to create the CloudFormation stack.

#### update.sh
Bash shell script utility to update the CloudFormation stack.

### Run the CloudFormation template with related parameters
To run the CloudFormation template and create the stack, use the following command

```bash
./create.sh project2stack ./project.yml ./project-parameters.json
```
The template exports outputs with the values of the various infrastructure elements. In order to easily test the project, use the value of the `LoadBalancerURL` key.

To test the live solution (at the time of submission) click here: [LoadBalancerURL](http://proje-AppLo-1RIS7DET4DWMM-152984625.us-east-1.elb.amazonaws.com).