## Deploying My Own Cloud | Task - 3


In this task, I am going to deploy my own cloud using Next Cloud which is a suite of client-server software for creating and using file hosting services. It is also free and open source which allows us to install on our own private server. Let see how it goes...

- I opened the Amazon LightSail and chose the **Ubuntu 20.04 LTS** Operating System(Have a Reason)
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627453881378/Vd3uL0XmL.png)

- I chose the $5 plan faster usage which is also free for three months
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627453939516/DcgDfulk4.png)

- After choosing the Instance type and gave the name as **NextCloud** and launched the instance.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454101033/TmxqsaX2l.png)

- It took seconds and launched the instance for deploying the NextCloud
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454160149/DYo-ZacRG.png)

- In the networking section, I added the **HTTPS**  protocol for later usage and since this is just testing deployment, avoided the static IP and used the existing public IP
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454216217/sg81yrQ_u.png)

- After the configurations, Launched the SSH using the browser
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454338348/6TPzKOxDR.png)

- I updated and upgraded the instance for the latest packages
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454362177/O6a2j7uUF.png)
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454407798/qrbK970ea.png)

- During the upgrading process, it asked me What to do about the modified configuration and I chose the Keep the local version currently installed. (Don't what that is...Anyone know Please Explain in the comments section)
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454656013/yaHyhVM38.png)

- As I chose the Ubuntu OS, it comes with a package manager called snap which makes this process easier and I installed the NextCloud using snap.

``` sudo snap install nextcloud ```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627454727627/6IzkBnOiK.png)

- After the installation, configured the nextcloud for login using the command
```sudo nextcloud.manual-installation <username> <password>```
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627455339888/i294NSPFB.png)

- When I looked about doing this work, Many of them integrated their sub-domain with this instance and that instance as trusted domain but I am not interested in doing that so I added the Public IP as the trusted domain.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627455582543/SIBfXFTo4.png)

> Forget to provision SSl during the process(But its ok!)
> If you want to provision SSL use the command : 
> sudo nextcloud.enable-https lets-encrypt
> this will automatically provision the SSL Certificate

- Then I opened the Public IP on the browser and gave the credentials to log into it.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627455647699/v9Jx2yUX4.png)

- After the successful login, I got my own personal cloud to store files and manage work
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627455725782/AL4_mLbU8.png)

- Since this is a test installation, I terminated the instance to avoid charges
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1627455842201/bK-Zv80fU.png)

### Conclusion
NextCloud had an awesome interface and tons of features. I am considering to open my own cloud in the future. 