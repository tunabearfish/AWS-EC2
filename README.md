## 📝 Prerequisites
  - Have an active AWS account


## 🛠 Set up


### 1. **Navigate to EC2 Dashboard**
![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/650ff413-0db6-4ea2-8698-2225bb342e45)



### 2. Launch an instance
You can start with giving your EC2 a name:

![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/ecfe7258-7b51-4051-87d0-044f2136797b)


For this example - We will go with AWS-EC2-Example

### 3. Choose Amazon Machine Image(AMI)
In this step: "Choose an Amazon Machine Image(AMI)" select an AMI that suits your requirements, AMI's are pre-configured tempaltes for different OS and applications.

![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/eacf53d2-4edf-4c9e-8c50-ded4d0104666)


For this example, we will choose Amazon Linux

### 4. Choose an Instance Type
In "Choose an instance Type": Select the instance type that meets your performance and resource needs. You can see additional details about each instance type( CPU, Memory, and Network Performance)

![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/5df56911-8b90-4bd1-adf5-698bbfec26dd)


For this example, we will choose t2.micro( this is a free tier)
### 6. Create a Key Pair
If you don't have an existing key pair, you'll need to create one. A Key Pair is used for secure SSH access to your instance

![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/0ce96176-6ce8-4fff-98ec-e0fe56d7378f)


For this example I already have one made
### 7. Configure Network settings
  Choose a VPC or create one(VPC's are required)

  ![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/5ce31941-ee42-4b5c-8ee3-69dd0c658cb6)


  I have chosen a default VPC
### 8. Configure Security Groups
  In the "Configure Security Group" step, you can either create a new security group or select an existing one. Security groups act as virtual firewalls for your instances, controlling inbound and outbound traffic.
![image](https://github.com/tunabearfish/AWS-EC2/assets/65553627/7e3cce92-2d58-4480-894e-7d5fd7a8b760)

  For this, I will be selecting a Security Group that I have already made
### 9. Configure Storage


### 10. Launch Instances

### 11. View instances


## 🚫 Troubleshooting

Encountered an issue? Consult the Troubleshooting Guide in this repository for guidance.
