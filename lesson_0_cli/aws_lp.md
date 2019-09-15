# Setting Up Our Development Environmnent - September 10, 2019

## Objectives
FWBAT...
* Set up their development environment on AWS EC2
* Understand how AWS fits in to larger cloud computing ecosystem 

## Vocabulary
* Server
* Cloud Computing
* Virtual Machine
* IaaS - Infrastructure as a Service
* AWS - Amazon Web Services
  - AWS EC2
  - AWS Cloud9
* IDE - Integrated Development Environment
* Development Environment

## The Why?
### AWS and Cloud Computing
* We will be using AWS Cloud9 as our **development environment**.
* It's easy. It's cheap. It can be accessed from anywhere. And it's more than enough to build a full stack application (and career!) on.
* Bonus: We get introduced to **cloud computing** the **AWS** ecosystem.
* Cloud Computing has fundamentally changed the way that we design, deploy, and use software.
* AWS is the global leader in **_cloud computing_** and it's not even close.
  * Microsoft, IBM, and Google are the closest competitor and AWS has more market share than all of them combined.
* Here's how Amazon define's cloud computing:
> Cloud computing is the on-demand delivery of compute power, database, storage, applications, and other IT resources via the internet with pay-as-you-go pricing.
> Whether you are using it to run applications that share photos to millions of mobile users or to support business critical operations, a cloud services platform provides rapid access to flexible and low cost IT resources. With cloud computing, you don’t need to make large upfront investments in hardware and spend a lot of time on the heavy lifting of managing that hardware. Instead, you can provision exactly the right type and size of computing resources you need to power your newest idea or operate your IT department. You can access as many resources as you need, almost instantly, and only pay for what you use.
* To unpack that, let's look at an example: Netflix
  - Netflix is built on AWS. What does a company like Netflix look like before/after cloud computing?
* To further illustrate, lets check out this video: [A Visit to the Cloud](https://youtu.be/94PO2-TL4Vs)

### Cloud9 and the AWS Ecosystem
* Cloud9 is "a cloud-based integrated development environment (IDE) that you use to write, run, and debug code".
  * An integrated development environment is an application that provides all the tools you need for software development in one location. They include a terminal, a text editor, and a graphical directory tree.
* Instead of running your code on your physical computer, Cloud9 creates a **_virtual machine_** for your code to run on. 
* Virtual machines are AWS most popular product. They offer them through a service called **_EC2 or Elastic Cloud Compute_**.
* Cloud9 and EC2 are just two of **over 100 services** that AWS offers to allow you to buid software, secure it, and deploy it to the world.
* Their ecosystem is so large that they offer a suite of certifications that you can obtain to signal your experience to potential employers.
* We will be working toward the [AWS Certified Developer - Associate](https://aws.amazon.com/certification/certified-developer-associate/) credential.

## Setting Up our Cloud9 Development Environment
1. Log into your AWS account. 
2. Change your password.
3. Once logged in, under "Find Services", type in "Cloud9".
4. Once at the Cloud9 homepage, click 'Create Environment'
5. Create your Cloud9 environment. 
  * **Step 1: Name Environment**
    Name: _firstName-marcylab_
    Description: This is the development environment for my Marcy Lab School projects and assignments.
  * **Step 2: Configure Settings**
    Leave all defaults as they are and click 'Next Step'
  * **Step 3: Review**
    Accept
6. Wait a minute while the environment configures. Once it's loaded, **save the link to your bookmarks**

## Touring the IDE
Demonstrate the following:
1. Manipulating your directory tree using the integrated terminal.
2. Creating and opening a text file.
3. Creating and opening an HTML file using 'Preview'
4. Changing the theme. 
