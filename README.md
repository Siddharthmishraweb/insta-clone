![Signup-login](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/b05f8444-cb99-4970-8d83-5d446a0192b3)# Instagram-clone-AspNetCore-React-Microservice

## Introduction
This is clone of Instagram built with Microservice Architecture with React and Asp.net Core. I have created this project to discover the world of Microservices and how they interact in Containerized environment. I have tried to experience the enterprise-level software development techniques like Docker container setup, development with decoupled services talking to each other using a Message Bus, separate environment for Production and Development, Git workflow and more.


## System Architecture
<p class="center">
    <img src="https://user-images.githubusercontent.com/63048473/101434729-f19eea00-392c-11eb-837e-f98583132e27.png">
</p>

### Highlights
CQRS pattern, Hangfire Job processing, RabbitMq Message Bus, Jwt Authentication, Docker Containerization, Nginx Proxy, Repository Pattern 


## Services
| Docker Image Name   | Details                      |
| ------------------- | ---------------------------- |
| rabbitmq_service    | RabbitMQ Message Bus Service |
| mysql_db_service    | Mysql DB Service             |
| mongo_db_service    | Mongo DB Service             |
| azurite_service     | Azurite Blob Storage Service |
| user_service        | User Service - .Net Core     |
| post_service        | Post Service - .Net Core     |
| newsfeed_service    | Newsfeed Service - .Net Core |
| nginx_service       | Nginx Apigateway Service     |
| web_service         | React SPA Web Application    |

## Database Schema
<p class="center">
    <img src="https://user-images.githubusercontent.com/63048473/100711198-c4a18300-33d2-11eb-82f1-95ab517fc57d.png">
</p>

## Main Technologies Used
|                  |                     |
| -----------------|---------------------|
| Asp.Net Core     | AutoMapper          |
| ReactJs          | FluentValidation    |
| Nginx            | FFMpegCore          |
| RabbitMq         | Azurite             |
| Docker           | Redux               |
| Docker-Compose   | Ant Design          |
| MySql            | Git Version Control |
| MongoDb          | Hangfire            |

## Application Over
view
### User can Sign Up & Login
<p class="center">
















![Signup-login](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/1b1dfaa1-cc1a-43b3-9de5-f5950cd8b071)



















    
</p>

### User can edit Bio
<p class="center">
















![Edit-bio](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/8783957e-3d80-49a0-8e4e-5e9de91b3f2e)























    
</p>

### User can add a Post
<p class="center">













![Add-Post](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/d6e4d7a5-3e26-477a-8cfa-c2dc45730d37)






















    
</p>

### UserProfile Walkthrough
<p class="center">














![Userfeed-overview](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/ebfa19bb-7475-4b08-badd-20b14e43823a)





















    
</p>

### User Newsfeed Walkthrough
<p class="center">














![Newsfeed-overview](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/308c8ab8-c2f3-4b35-988e-daa70d629a8c)






















    
</p>

### Realtime Newsfeed Update
<p class="center">











![Realtime-Newsfeed-new (1)](https://github.com/Siddharthmishraweb/insta-clone/assets/72328255/009fdc31-39e0-466e-bb03-30b30f40c4c1)



















    
</p>

## How to get Project Up & running -- In Development Environment
1. Clone this Repo
2. Run following commands:\
    `cd src/`\
    `dotnet build`\
    `cd ../scripts/`\
    `docker-compose -f docker-compose.dev.yml build`\
    `docker-compose -f docker-compose.dev.yml up`
3. You can now visit https://localhost:4430/ in your browser!

[comment]: # (> Seed Data:)
[comment]: # (> Emails: ironman@gmail.com | spiderman@gmail.com | superman@gmail.com | hulk@gmail.com)
[comment]: # (> Password: User@123)

## How to get Project Up & running -- In Production Environment
[In Development]

