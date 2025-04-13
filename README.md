# Welcome to an AWS / Splunk Federated MacGyver Workshop
#### a T-REX production

<p align="center">
<img src="/static/federatedmacgyverlogo.png" width="300px" >
</p>

## Overview 

Welcome to the Splunk and AWS Federated MacGyver workshop. This workshop forms part of the AWS Workshop platform found <a>[TBD](<TBD>) </a>

In this workshop, we take a look at three AWS log examples of data which could be a suitable candidate for Federated Searching.
>[!NOTE]
> These labs are guidence only. Each companies requirements and what is a suitable use case for federated searching are different. You should 
> always work with your Splunk or Splunk partner specialist to make sure the use cases you are wanting to deploy are suitable. Using federated
> search on the wrong use cases can be less performant and more expensive overall than traditional ingestion patterns.

Now that the disclaimer is out the way, let's look into the labs for today. 
1. LAB 1: VPC Flow Logs
2. LAB 2: Web Applicagion Firewall (WAF) Logs
3. LAB 3: Cloudfront Access Logs

The aim for these labs is to explore different methods of configuring AWS Glue and Athena which is then used to search data from Splunk. 
This knowlege can then be applied to many different use cases and log types. 


>[!NOTE]
> -This workshop is expected to take approximately 2-3 hours to complete.<br>
> -This workshop is created for target audiences like Cloud Architects, Security Analysts and Splunk Administrators.<br>
> -The participants are expected to have a general experience with AWS products and services, along with basic knowledge Splunk, Splunk Apps and running Splunk SPL Queries.<br>
> -This workshop is not inteded to be run as part of a joint AWS and Splunk event. These labs should work in your own AWS envirnoemnt <br>
> -To make things easier we have already configured the AWS add-on on your Splunk service including an index called `aws-data` for you to use. Please use these are part of the labs. 

>[!IMPORTANT]
>Please make sure you sign out or use an incognito tab when using your AWS console as you do not want to accidentally use your work/personal AWS account and end up with a bill or get in trouble
>TRUST ME, it has happened to people!!

Once you have completed this workshop you will end up deploying the following archiecture pattern:

![gdi_architecture](/static/gdi_workshop_architecture.png)

## Time to get to get started!
Below are the links to each of the labs

<a>[LAB1 - EC2 metadata and AWS Config logs to Splunk via AWS add-on PULL method](/content/Lab1_awsaddon/index.en.md) </a>

<a>[LAB2 - Amazon EventBridge notification using native EventBridge PUSH method ](/content/Lab2_eventbridge/index.en.md) </a>

<a>[LAB3 - CloudTrail logs to Splunk via Amazon Data Firehose PUSH method ](/content/Lab3_firehose/index.en.md) </a>

<a>[LAB4 - VPC Flow logs to Splunk via Amazon Lambda PUSH method ](/content/Lab4_lambda/index.en.md) </a>

<a>[LAB5 - Explore our data using Splunk ](/content/Lab5_data_exploration/exploring_data_1.md) </a>

