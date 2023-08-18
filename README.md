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

<img width="1288" alt="bedrock-redis-rc-6" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/bae55fb8-13d4-4900-9a0e-6ae42883a359">

Once connected successfully, you will see a message at the top ( see annotation 1) and now you can get started. In this case, since a "Free Trial" option is chosen, you will see a `Start free trial` option.
Go ahead and click on `Start free trial`.

<img width="1288" alt="bedrock-redis-rc-7" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/d05c6e4a-68ac-4fc8-a9df-c6b387be8c8d">

As soon as you login, you will see this UI. Notice that there is a Free Trial banner at the top. Ignore this banner, if you are not on a promotional free tier.
1. Appearance of `AWS Marketplace` icon, indicates that your Redis account is now connected to your AWS account.
2. On the `Setup` tab, you will see cloud vendors.
3. Go ahead and select `AWS` if it is not highlighted and selected already.

<img width="1288" alt="bedrock-redis-rc-8" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/a279a43c-aa4f-41ae-95e0-f069cfd7bf33">

Go ahead and select your `Region` and give `Subscription name` a name.

<img width="1288" alt="bedrock-redis-rc-10" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/9d204251-2399-43a1-a406-869af7769986">

`Redis 7.2` is now available for you to choose. This is the latest and greatest offering from Redis. Select it.

<img width="1288" alt="bedrock-redis-rc-11" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/9337ab30-208e-4e4f-a2d2-c485a0c6fe39">

Choose a `Region` and a `CIDR`, like what is shown below.

<img width="1288" alt="bedrock-redis-rc-12" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/68ac390f-559a-489b-a62f-a3d5216c27f9">

Simply choose default values here.

<img width="1290" alt="bedrock-redis-rc-13" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/544c0942-4515-460f-9706-a56d44f7f0eb">

On the `Sizing` tab, click on `+` button to add a new database.

<img width="1290" alt="bedrock-redis-rc-14" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/5214845a-d3c6-49c1-b3d1-7eec57059876">

Give your `database` a name and select `RediSearch` and `RedisJSON` modules.

<img width="1288" alt="bedrock-redis-rc-15" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/6d449812-b920-4f5e-9f59-cb0e7878df3d">

Depending upon the total data volume, you are going to start with a specific data size and throughput needed for your applications. For this hands-on exercise, just choose a minimalistic configuration ( example: Memory = 1 GB and Throughput Shards = 1).

<img width="1288" alt="bedrock-redis-rc-21" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/3dafeb05-c1d1-411f-bace-7bd5ed921334">

Once you review the total cost price, and other details, simply click on the `Create subscription` button to create `Redis Enterprise Cloud Flexible` subscription.

<img width="1288" alt="bedrock-redis-rc-22" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/f0581b95-a855-46ca-a11f-2eeed535f3d4">

The actual subscription creation may take approximately 5 mins to 15mins.

<img width="1288" alt="bedrock-redis-rc-23" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/e8c82094-81cd-4c06-b519-50dd0bad44fe">

Once the subscription is created, you will see that it is ready with a Green amber light on in the `Status` column.

<img width="1288" alt="bedrock-redis-rc-24" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/36af6ccf-a789-46eb-913e-24f354eee3df">

If you click on the database, the database configuration screen shows that the TLS is turned off by default. Click on Edit button to edit the details.

<img width="1288" alt="bedrock-redis-rc-25" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/3dfae120-a999-450b-a6ed-74260f84e37b">

Go ahead and turn on the TLS (`annotation 1`), disable `TLS client authentication` (`annotation 2`) and download the server certification (`annotation 3`).
Finally `Save the database` (`annotation 4`)

<img width="1288" alt="bedrock-redis-rc-28" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/43b222c0-cd89-48b2-b882-03507ecd019d">

Redis Enterprise Cloud on AWS is now ready for your use. Typically, the developers need an endpoint , a user password and the server certificate to connect to the database from their applications.

<img width="1288" alt="bedrock-redis-rc-30" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/0a8a13b6-4a7b-421f-a900-0186d2391d75">

Redis web console also gives you code snippets on how to connect from different clients. Choose the one that is appropriate to your client applications.

<img width="1288" alt="bedrock-redis-rc-31" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/8946edae-e0d4-4e86-8ac9-e9d38bebe618">

Like mentioned above, here is how you can get the password to your Redis database.
<img width="1290" alt="bedrock-redis-rc-32" src="https://github.com/RedisVentures/aws-redis-bedrock-stack/assets/6223831/15671058-1040-4f9b-8858-9669970c6112">

### Summary
In essence, you will spin a Redis Enterprise Cloud cluster in AWS and once this subscription is provisioned, you will need the following details for your database, for your client applications to connect to.

```
Redis Enterprise Cloud Database Hostname
Redis Enterprise Cloud Database Port Number
Redis Enterprise Cloud Database Password
Redis Enterprise Cloud Database Server certification for TLS
```
