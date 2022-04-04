# AWS-Elastic-Beanstalk-Code-Pipeline-git

[![Build](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Description

AWS Elastic Beanstalk is an orchestration service offered by Amazon Web Services for deploying applications which orchestrates various AWS services, including EC2, S3, Simple Notification Service, CloudWatch, autoscaling, and Elastic Load Balancers.Pipeline as code is a practice of defining deployment pipelines through source code, such as Git. Pipeline as code is part of a larger “as code” movement that includes infrastructure as code. Teams can configure builds, tests, and deployment in code that is trackable and stored in a centralized source repository.

AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates.

## Pre-Requests
```
Basic knowledge on AWS,  Elastic Beanstalk and Code pipeline
Git repo for the setup
```
> I have uploaded my website contents on https://github.com/jomyg/My-custom-simple-basic-website

> First of all create a Elastic Beanstalk application environment, Here i have used the tomcat as i have to host my website via git. I have already confgured my git account with my aws account.
> After the deploy of Beanstalk application environment completed, we can move on to the Code pipeline for the source code deployment to Beanstalk, I have used the git version 1 which have only the webhooks setup. When we commit any changes on our website contents its will trigger and Beanstalk will deploy the new contents to EC2 via Code PIpeline. I have attached all the snapshots of steps below. Pleas follow and let me know if you have any queries. 


<center><img alt="aws" src="1-beanstalk.png"> </img></center>
<center><img alt="aws" src="creationinprogress-02.png"> </img></center>
<center><img alt="aws" src="creationcompleted-03.png"> </img></center>
<center><img alt="aws" src="4-pipeline-creation.png"> </img></center>
<center><img alt="aws" src="6-deploying.png"> </img></center>
<center><img alt="aws" src="7-creation.png"> </img></center>
<center><img alt="aws" src="10-site.png"> </img></center>
<center><img alt="aws" src="11-secondcommitdoneongit.png"> </img></center>
<center><img alt="aws" src="12.png"> </img></center>
<center><img alt="aws" src="13-changes-triggers.png"> </img></center>
<center><img alt="aws" src="14site.png"> </img></center>


## Conclusion

Deployed my website via AWS Elastic Beanstalk and Code pipeline using git

<center><img alt="aws" src=""> </img></center>

#### ⚙️ Connect with Me

<p align="center">
<a href="mailto:jomyambattil@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/jomygeorge11"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> 
<a href="https://www.instagram.com/therealjomy"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a><br />
