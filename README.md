# appscan-issue-gateway-rtc

The AppScan Issue Management Gateway service helps to synchronize issues between [IBM Application Security on Cloud](https://appscan.ibmcloud.com/)
and other issue management systems such as IBM Rational Team Concert. This capability should appeal to any AppScan users who need security 
issue data "pushed" into other systems and want to avoid building all the REST calls and plumbing themselves.  This service itself operates as a REST API, 
but as you'll see below the intent is to make this as painless as possible. 

The ideal use case for this service is as a part of an automated scanning workflow where it is getting called when necessary to perform the issue processing.

Youtube Links:

- Part 1: [https://youtu.be/7-a18ypMpM4](https://youtu.be/7-a18ypMpM4)
- Part 2: [https://youtu.be/_lsozLQ5CnM](https://youtu.be/_lsozLQ5CnM)

# Prerequisites:

- A Java 8 Runtime
- A REST Client (such as "curl" or your language of choice) to submit requests to the service 
- An [IBM Application Security on Cloud API Key](https://www.ibm.com/support/knowledgecenter/SSYJJF_1.0.0/ApplicationSecurityonCloud/appseccloud_generate_api_key_cm.html)
 