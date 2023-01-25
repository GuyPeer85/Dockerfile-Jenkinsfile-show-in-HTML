# dockerfile-jenkinsfile-show-in-html
Here you can see the diagram of the pipeline:
============================================

![docker jenkins class project diagram drawio](https://user-images.githubusercontent.com/106809238/214575536-7b6f5e89-9303-421c-8c50-ab24844258b0.png)

Explanation of the steps:
-------------------------
step: 1
1. User choose language and mail the send the resulte
2. Jenkins run by connecting to the github 
3. The job clone github full repository

step: 2
1. the job read the dockerfile from the choosing repository

step: 3
1. The job build the image from the dockerfile
2. The job run the image that created and connect it to apache httpd

step: 4
1. The job send by mail and Jenkins platform the resulte with link to see the text resulte

