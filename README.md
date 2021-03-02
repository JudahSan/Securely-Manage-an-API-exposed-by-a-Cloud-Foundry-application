# Securely-Manage-an-API-exposed-by-a-Cloud-Foundry-application

## Step 1

Signup/Sign-in on IBM Cloud: https://ibm.biz/Bdfscz

## Step 2 Create an application in the Cloud Foundry "Public" environment

Select Cloud Foundry from navigation menu

<img width="599" alt="1" src="https://user-images.githubusercontent.com/16270682/109646074-252a9280-7b71-11eb-968b-b7a4487d5cf3.PNG">

Click on "create" under "Public Application" 

<img width="941" alt="2" src="https://user-images.githubusercontent.com/16270682/109646288-72a6ff80-7b71-11eb-8660-7eeeb8b8c67b.PNG">

Select free plan -> Select SDK for Node.js -> give your application a unique name -> click create

<img width="649" alt="3" src="https://user-images.githubusercontent.com/16270682/109646407-966a4580-7b71-11eb-83ad-6d1676a10789.PNG">

<img width="909" alt="4" src="https://user-images.githubusercontent.com/16270682/109646770-f103a180-7b71-11eb-936a-5cde7a828586.PNG">

Visit your application and copy your application url 

<img width="666" alt="5" src="https://user-images.githubusercontent.com/16270682/109647690-0927f080-7b73-11eb-8f5f-6c4c7026702e.PNG">

## Step 3 Create an API using "API Gateway"

From navigation menu select API Management 

<img width="460" alt="6" src="https://user-images.githubusercontent.com/16270682/109648359-f6fa8200-7b73-11eb-9fbe-128776c1d63d.PNG">

Select services -> API Gateway

<img width="939" alt="7" src="https://user-images.githubusercontent.com/16270682/109648385-fd88f980-7b73-11eb-9aa0-0e29d6dc953c.PNG">

From managed API's select API proxy

<img width="939" alt="8" src="https://user-images.githubusercontent.com/16270682/109648412-05e13480-7b74-11eb-872d-79e3db54eba3.PNG">

Give your API a unique name, in the exteral URL field paste your application url that you copied in step 2
<img width="918" alt="9" src="https://user-images.githubusercontent.com/16270682/109648435-0d084280-7b74-11eb-8f87-02fc07b77ae9.PNG">

Your API is ready and live, copy your API route address and open it in new window. 
<img width="890" alt="10" src="https://user-images.githubusercontent.com/16270682/109648460-1396ba00-7b74-11eb-90cb-c3a73c9cd1b0.PNG">

You have managed to securely expose a cloud Foundry application. 


