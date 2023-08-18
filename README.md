-------
# Redis Enterprise Cloud on AWS - Flexible Pay-as-you-go with 14 days FREE TRIAL - A How to Guide

## Introduction

Did you know that [Redis](www.redis.com) now offers a FREE Trial for [Redis Enterprise Cloud on AWS - Flexbile Pay-as-you-go with 14 days FREE TRIAL](https://aws.amazon.com/marketplace/pp/prodview-mwscixe4ujhkq?sr=0-11&ref_=beagle&applicationId=AWS-Marketplace-Console)?  With this option, you get $500 USD worth of AWS credits over the course of 14 days. After that, you can transition in to a "Pay-As-You-Go" customer and pay only for your usage.  If you don't believe this, you can try it out yourself, by following these instructions.

## Instructions

Lets start with AWS Marketplace. A simple search for `Redis` yields you to the following highlighted `Redis Enterprise Cloud` offerings from Redis.
Notice you have two products to choose from:
* Redis Enterprise Cloud Flexible - Pay as you go option.
* Redis Enterprise Cloud Annual Commit

Go ahead and choose `Redis Enterprise Cloud Flexible` option for this hands-on exercise.
<img width="1296" alt="bedrock-redis-rc-1" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/f25c94a6-6a36-4369-91bd-bcc15679ebda">


Continue to click on `View purchase options`

<img width="1296" alt="bedrock-redis-rc-2" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/eb1cd0df-a00d-43b2-ae06-92a019197383">

On the product page,
1. Click on the `Subscribe` button. This button gets greyed out after you click on it for the first time.
2. Then the banner highlighted at the top, will appear.
3. On this banner, go ahead and click on `Setup your account`.

<img width="1296" alt="bedrock-redis-rc-3" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/f9e54a8f-86cc-4ec5-a4c6-e07836ce7616">

This navigates you to the sign-in page of `Redis Enterprise Cloud` web console.

<img width="1288" alt="bedrock-redis-rc-4" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/8381a74e-e7ca-4902-a392-5909d71b48e9">

As soon as you sign in , you will see that your `AWS Account` ( example: `Srini 1320974`) is displayed and you will be able to connect this AWS account with Redis Enterprise Cloud web console.
Go ahead and check the selection box highlighted.
<img width="1288" alt="bedrock-redis-rc-5" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/a8b1c0a3-0281-4532-bea8-053bb3b53b9d">

Click `Connect account`. This will connect your AWS account with "Redis Enterprise Cloud" web console.

<img width="1288" alt="bedrock-redis-rc-6" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/60aeef51-825e-40b1-9cf3-349cc953f142">

Once connected successfully, you will see a message at the top ( see annotation 1) and now you can get started. In this case, since a "Free Trial" option is chosen, you will see a `Start free trial` option.
Go ahead and click on `Start free trial`.

<img width="1288" alt="bedrock-redis-rc-7" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/48d7e582-d064-4fb1-b1b2-a9214c8aa249">

As soon as you login, you will see this UI. Notice that there is a Free Trial banner at the top. Ignore this banner, if you are not on a promotional free tier.
1. Appearance of `AWS Marketplace` icon, indicates that your Redis account is now connected to your AWS account.
2. On the `Setup` tab, you will see cloud vendors.
3. Go ahead and select `AWS` if it is not highlighted and selected already.

<img width="1288" alt="bedrock-redis-rc-8" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/16fee76d-e88a-4c80-b02b-99830220fa19">

Go ahead and select your `Region` and give `Subscription name` a name.

<img width="1288" alt="bedrock-redis-rc-10" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/9e1e38e8-d6f7-4ebb-8cad-f67bbaabd2e3">

`Redis 7.2` is now available for you to choose. This is the latest and greatest offering from Redis. Select it.

<img width="1288" alt="bedrock-redis-rc-11" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/f5d5e6ac-14e4-49ed-8bd6-c27a95dd656f">

Choose a `Region` and a `CIDR`, like what is shown below.

<img width="1288" alt="bedrock-redis-rc-12" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/7f090fe5-e1de-4d25-852f-4906ed36a9f6">

Simply choose default values here.

<img width="1290" alt="bedrock-redis-rc-13" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/11608ab6-0e46-4ae4-90cb-a4dca0dcc926">

On the `Sizing` tab, click on `+` button to add a new database.

<img width="1290" alt="bedrock-redis-rc-14" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/cbfe4889-7739-44fa-9232-4d98b31c31d5">

Give your `database` a name and select `RediSearch` and `RedisJSON` modules.

<img width="1288" alt="bedrock-redis-rc-15" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/a7a04d1e-f757-430e-bc55-8a9c95b65217">

Depending upon the total data volume, you are going to start with a specific data size and throughput needed for your applications. For this hands-on exercise, just choose a minimalistic configuration ( example: Memory = 1 GB and Throughput Shards = 1).

<img width="1288" alt="bedrock-redis-rc-21" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/976fec81-99d3-403c-9da7-98e27873a55c">

Once you review the total cost price, and other details, simply click on the `Create subscription` button to create `Redis Enterprise Cloud Flexible` subscription.

<img width="1288" alt="bedrock-redis-rc-22" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/2e424f9f-594d-40fe-b218-ec7cb50d2374">

The actual subscription creation may take approximately 5 mins to 15mins.

<img width="1288" alt="bedrock-redis-rc-23" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/18b59ead-a921-487f-8b25-00b83175fd85">

Once the subscription is created, you will see that it is ready with a Green amber light on in the `Status` column.

<img width="1288" alt="bedrock-redis-rc-24" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/2f23c26a-4aa0-4b4d-9908-23fc46b16b62">

If you click on the database, the database configuration screen shows that the TLS is turned off by default. Click on Edit button to edit the details.

<img width="1288" alt="bedrock-redis-rc-25" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/4e67ecca-c14e-45a6-9135-18bec9eb2dc7">

Go ahead and turn on the TLS (`annotation 1`), disable `TLS client authentication` (`annotation 2`) and download the server certification (`annotation 3`).
Finally `Save the database` (`annotation 4`)

<img width="1288" alt="bedrock-redis-rc-28" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/ab2e671c-7c2f-434f-8074-7132e4bd88eb">

Redis Enterprise Cloud on AWS is now ready for your use. Typically, the developers need an endpoint , a user password and the server certificate to connect to the database from their applications.

<img width="1288" alt="bedrock-redis-rc-30" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/aa14e3a5-23c2-4d8b-8536-f1605f9bd72c">

Redis web console also gives you code snippets on how to connect from different clients. Choose the one that is appropriate to your client applications.

<img width="1288" alt="bedrock-redis-rc-31" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/347a7131-c377-44f1-ac5c-58bba5753421">

Like mentioned above, here is how you can get the password to your Redis database.
<img width="1290" alt="bedrock-redis-rc-32" src="https://github.com/spendyaala/how-to-guide-aws-redis-free-trial/assets/6223831/49c15912-e0b3-44fe-895a-9e1cdee69711">

## Summary
In essence, you will spin a Redis Enterprise Cloud cluster in AWS and once this subscription is provisioned, you will need the following details for your database, for your client applications to connect to.

```
Redis Enterprise Cloud Database Hostname
Redis Enterprise Cloud Database Port Number
Redis Enterprise Cloud Database Password
Redis Enterprise Cloud Database Server certification for TLS
```
