# GOAL of this project

The goal of this project is to create a new cloud-based server for an end-user.

## Aren't there enough cloud solutions already?
Yes, there are. Popular ones include Google Drive, Microsoft OneDrive, iCloud Drive (by Apple), Box and Dropbox. However, they are all created, managed and maintained by the companies that make them. When we (end-users) upload content on them, we hand over our data to those companies and agree to the terms and conditions put up by them. Some of those terms might be written in enough legalese that allows them to look inside the data). 

While that can be helpful and/or useful for either/both the user and the provider, the end-user might not always want to let the service provider look into the contents. This is where self-hosted projects become necessary. When it comes to hosting a cloud solution on your own server, there are not many options. 

One of the most popular solutions is called nextCloud (which is the successor of ownCloud). The deployment is not simple enough that you can just launch a program or a docker container and get ready to work with it. Configuring and tuning the service is one of the primary headaches upfront. Also, it is written in PHP, so compared to compiled languages, the solution does run slow. 

There is another solution named Seafile which acts as just a file-syncing service but is just good enough for file syncing, is written in C and python and can be used to 

## What does this project aim to do
This project aims to create an end-user cloud (this repo is for the server) which is:

1. easy to deploy (in a single command)
2. runs fast
3. is secure
4. has as less dependencies as possible
5. can be scaled to multiple servers if needed
6. can be deployed on multiple operating systems
7. can eventually be used as a primary cloud storage solution

While the long term goal is to be as capable as possible in terms of functionality, the current primary goal is to be able to act as a file storage and sync server.

