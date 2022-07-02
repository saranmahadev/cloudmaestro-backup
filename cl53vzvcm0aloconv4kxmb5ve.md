## Well, I build an another Google...(Seriously I did)!

## Introduction

In the internet, no one can offer services for free without servers. Google is spending more than 25 Billion dollars in servers for offering different services. So how do they pay their bills? how a free search engine can provide service to billions of users at the lowest latency possible in the market. Well, they make you as a product and sell you to different companies. 

## You are Sold!

Google has your

- Search interests
- Video interests
- Calendar
- Files
- and more...

So Google knows you better than your parents😸! They sell all your interests to the product companies and show personalized to gain revenue. There is a big legal aspect behind this problem and as a developer I don't care (Most of the citizens in the world's attitude)!

## What are u going to do about it?

Some people are really angry and care about their privacy very seriously and they have addressed this issue with creating various open source solutions. Seriously, there is lot of alternatives. So lets replace Google!

### Google Search

For replacing, I went with **SearXNG**,  a free internet metasearch engine which aggregates results from more than 70 search services where the users are neither tracked nor profiled.

Step By Step Procedure Installation:

1. Create a VM instance (a server) in any cloud platform, I went with Microsoft Azure.

![vm.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656749810470/aUPDri-b8.png align="left")

2. Make sure to install git, docker and docker-compose installation in the instance.

```
sudo apt-get install git docker.io docker-compose
```
![reqs.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656750001247/SI6t7Rtje.png align="left")

3. Get the docker-compose version of **searchxng**.

```
git clone https://github.com/searxng/searxng-docker.git
```

4. Move into the directory and edit the `.env` file, add your domain and email address to the file.

![env.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656750180122/9nc1VGMht.png align="left")

5. Let's start the engine.

```
docker-compose up -d
```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656750410729/BrMBH-Csm.png align="left")

### Google Drive, Sheets, Slides, Docs

Next Cloud is an awesome solution and I have interacted with already and decided to use it as a full time solution. Used the same docker and configured the drive.saranmahadev.tech

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656765847885/rpEsUQl68.png align="left")

### Gmail

Attained my own email server, a very long time ago...

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1656765974754/ioVxDZ5OR.png align="left")


## Conclusion

So I have tried my best to attain maximum privacy and basically recreated Google with different open source projects and if you have suggestion that can replace enterprise level companies tracking, let me know in the comments!

