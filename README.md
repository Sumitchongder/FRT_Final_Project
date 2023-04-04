# Future Ready Talent Project by Sumit Tapas Chongder

## About The Project:
 This is a sample project created for the purpose of learning and demonstration of Microsoft Azure skills during the Future Ready Talent Program

This is a simple Educational Blog website. It is a responsive front-end static website designed by using HTML, CSS and JavaScript. It allows the users to have a look on layout of the website having different features. Any user (Programmer) can have a look on different features of layout of the webiste like Home, About, Category, Pages, Contact Us, etc.
This website provide every single update in this technical world to the user. 
Therefore, this project is not intended for commercial deployment.

## Azure Services Used: Web Apps, Static Web Apps, Storage Accounts.

#### Azure Storage Accounts: Azure Storage Accounts provide scalable and secure cloud storage for various types of data, including blobs, files, queues, tables, and disks. In this project, I have utilized containers in storage account to store the Images used in the webpage
#### Azure Static Web Apps: Azure Static Web Apps is a cloud-based service that simplifies the deployment of static web applications and provides built-in continuous deployment, authentication, and serverless APIs. In this project, I have utilized Static Web Apps to deploy/host the webpage
Note: Used Lorem Ipsum content for sample website.

### Azure Deployment URL: https://jolly-plant-0cc8d9910.2.azurestaticapps.net
### GitHub Deployment URL: https://sumitchongder.github.io/FRT_Final_Project/

## How Azure Services are consumed in this Project: Literate Web App [Steps to Create & Utilize are shown below]
## First Azure Service: Storage Accounts

Firstly, we'll create a storage account in which to store all the images needed for or used by our webpage.

![FRT 7](https://user-images.githubusercontent.com/77958774/227234439-178f62bf-8ca2-4eee-8e91-63bad58b288a.png)

Following that, we will create a Container to hold all of the images, and we will drag and drop each image into the Container.

![FRT 8](https://user-images.githubusercontent.com/77958774/227234636-c33e76d1-3492-4dc4-a0ec-d6bce18dedd8.png)
![FRT 9](https://user-images.githubusercontent.com/77958774/227234984-e30c60dc-c209-4bd8-8dbb-d99607f75676.png)

Within the Storage Accounts|Container -> frtprojectimages, I have stored all the Images that are been used in the Webpage Development.

![FRT 11](https://user-images.githubusercontent.com/77958774/227235138-24fa3100-45fa-4536-b431-5fe21addcc33.png)
![FRT 10](https://user-images.githubusercontent.com/77958774/227235221-122ed3cd-807e-4275-bb61-f4cb83e70503.png)

### Some Storage Accounts|Containers -> Images links to verify/demonstrate the use of Storage Account Service in this Project.
 https://frtproject92cd.blob.core.windows.net/frtprojectimages/join.jpg   
 https://frtproject92cd.blob.core.windows.net/frtprojectimages/banner.jpg
 https://frtproject92cd.blob.core.windows.net/frtprojectimages/logo1.png
 https://frtproject92cd.blob.core.windows.net/frtprojectimages/team1.jpg
 https://frtproject92cd.blob.core.windows.net/frtprojectimages/about.jpg
 https://frtproject92cd.blob.core.windows.net/frtprojectimages/avatar1.jpg
https://frtproject92cd.blob.core.windows.net/frtprojectimages/avatar4.jpg


## Second Azure Service: Web App, Static Web App

We will develop a web app to host our website after generating the storage account.

![FRT 1](https://user-images.githubusercontent.com/77958774/227236657-b55173d0-154a-47c1-b6ce-c1c6cb67479c.png)

The Web App asks us whether we want to deploy the Code, Docker Container or Static Web App, we select Static Web App to deploy our Website & follow the steps given below to create the Static Web App.

![FRT 2](https://user-images.githubusercontent.com/77958774/227237622-cfc07c3f-168c-4116-87d2-24a73b7be849.png)
![FRT 3](https://user-images.githubusercontent.com/77958774/227237721-bfccebbe-bb78-4c81-86a3-de575c8bea43.png)
![FRT 4](https://user-images.githubusercontent.com/77958774/227238136-31a2a36e-be08-4f8f-8baf-df9e5fa4b1e2.png)
![FRT 5](https://user-images.githubusercontent.com/77958774/227238331-5f715e33-31b1-4316-a60a-9b0dfdfd4eea.png)
![FRT 6](https://user-images.githubusercontent.com/77958774/227238418-95a3aea8-7624-47ba-874c-b7a941c47e8a.png)

## Integrating Storage Account with Static Web App
Inorder to Integrate the Storage Account with Static Web App we navigate to the Settings of the Static Web App and in the Configuration we click on Application Settings and Click on Add Option and Paste the URL of the Storage Account.

![FRT 13](https://user-images.githubusercontent.com/77958774/227265203-3a4e1eb2-3f38-4578-b714-2730e1dbfbaf.png)
![FRT 12](https://user-images.githubusercontent.com/77958774/227263458-b0b7b7ec-25d8-4bc3-a09a-b3a5860ab09f.png)

## Project Demo Screenshots:
![Screenshot (93)](https://user-images.githubusercontent.com/77958774/227239584-69860598-c939-4742-b725-192493c31965.png)
![Screenshot (94)](https://user-images.githubusercontent.com/77958774/227239730-ac60c8c6-0616-4175-9a5f-bbcae33bf610.png)
![Screenshot (95)](https://user-images.githubusercontent.com/77958774/227239796-560ed3c7-8c1f-49a5-936e-373b1e647e05.png)
![Screenshot (96)](https://user-images.githubusercontent.com/77958774/227239814-8c637fba-4bf9-4ea5-9bc0-810a200eafeb.png)
![Screenshot (97)](https://user-images.githubusercontent.com/77958774/227239841-64eb63d2-696c-4153-8b8c-c5226b249494.png)
![Screenshot (98)](https://user-images.githubusercontent.com/77958774/227239876-d5b7c3fd-b12c-4e18-b963-2500ec52ebeb.png)
![Screenshot (99)](https://user-images.githubusercontent.com/77958774/227240017-d05ca115-94fd-4279-a9d0-bbd5b59a54c3.png)
![Screenshot (100)](https://user-images.githubusercontent.com/77958774/227240057-b808996b-0973-4204-a3df-0e109ac5e566.png)

## Layouts:
 This is a single page website and it has pretty responsive and animated layout for user to catch attention.
Has a logo and name of the Educational blog on the top-left of layout.
Has different features visible on the navigation bar of the layout.
It contains Some highlights of the blog.
Also it contains blogs on trending technologies and few posts too.
Has added social media handles so that user can connect with us.
For getting updates via mail, user can add their email id and subscribe so that they can get latest updates via mail.
Any user can share its information related to technical topic to all users after creating their account here.

## Drawbacks:
 Does not contain real details of the website as it is a sample website.
Does not have back-end so there is minimal functionality.
Can not save information as it does not have database.


## Steps to run the project:
 Clone or download source code from Github.
You can download it directly, or use a tool like Git-bash, tortoise git...
Run this source code, depending on the language of the source code.
