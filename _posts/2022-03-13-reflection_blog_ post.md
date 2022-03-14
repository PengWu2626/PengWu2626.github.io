---
layout: post
title: Reflection Blog Post
---

Our group (**Peng** (myself), **Jiamu**, **Weixin**, and **Miao**) made the web app called **Dog Facial Recognition**. Our web app used three machine learning models. First, our web app will detect if the image contains any human face. Then, it will detect the uploaded image is a dog or cat. Finally, the web app will show the top three most likely dog breeds.

- [Here is the link to the GitHub repository containing the code of this project.](https://github.com/PengWu2626/PIC16B_GroupProject)

- [Here is the Heroku link for our web app.](https://pic16b-dog-facial-recognition.herokuapp.com/) (Long Boot Time)

- [Here is the Heroku link for the short version of our web app](https://pic16b-dogfr-short.herokuapp.com), which removed face detecting and the drop zone.

## Overall, what did you achieve in your project? 

I mainly designed this project, assigned minimal tasks to each group member that they must do, and helped our group members with any questions. For instance,  I asked Jiamu to write a face detection model to determine if the user uploaded image contains any human face. Also, I assigned each of Weixin and Miao to build two different models using transfer learning for dog breed classification.

My main achievement for this project is to make sure our webapp is working. I gathered all models from our group members, did image processing inside our webapp, and wrote the view page to display the results from each model. I had many ideas that popped up while building our webapp, so I decided to write some extra features in our webapp.

Extra Features:

- I wrote a `web scraping` called [DogTime Scraper](https://github.com/PengWu2626/PIC16B_GroupProject/tree/main/DogTime_scraper) to get all characteristics for each dog breed from the [DogTime](https://dogtime.com/dog-breeds/profiles).

- I wrote a `Drag Upload` page and all relative codes that contain a [Drop zone](https://flask-dropzone.readthedocs.io/en/latest/index.html) that allows the user to drag an image to upload.
<img src="/images/reflection_blog_ post_images/Drag_Upload_Page.png" alt="Drag Upload Page Image">  

- I wrote a `Click Gallery Upload` page and all relative codes to display all user-uploaded images, and users can click on each image to get the predicting result from our models. 
<img src="/images/reflection_blog_ post_images/Click_Gallery_Upload.png" alt="Click Gallery Upload Image"> 

- I wrote a `DogTime Information` page and all relative codes to generate bar charts with 26 characterizes that I scraped from Dogtime from a user-selected dog breed.
<img src="/images/reflection_blog_ post_images/DogTime_Information.png" alt="DogTime Information Image"> 

- I wrote the `Find Your Best Dog` page and all relative codes to find matched dog breeds from the user-selected numbers.
<img src="/images/reflection_blog_ post_images/Find_Your_Best_Dog.png" alt="Find Your Best Dog Image"> 




## What are two aspects of your project that you are especially proud of? 

1. Adding CSS and Javascript made our webapp more interactive and beautiful. Therefore, I searched for many cool effects that we can use inside our web page. I modified some cool CSS effects codes that I found online. For example, I combined these two beautiful [Parallax Star backgrounds](https://codepen.io/saransh/pen/LYGbwj) and [Shooting Star backgrounds](https://codepen.io/alphardex/pen/RwrVoeL) and added the [Glassmorphism](https://hype4.academy/tools/glassmorphism-generator) effects. Unfortunately, I did not have any prior experience with CSS and Javascript, and I had to use them inside many for loops, which increased the difficulty of building our webapp. 


2. I successfully developed our webapp on Heroku. In the beginning, I used `pip freeze` and copied all dependence names inside the [requirements.txt](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/requirements.txt). No surprise, the slug size was way too large. So I created another short version of this project in the [pic16b_group_project_short_version](https://github.com/PengWu2626/pic16b_group_project_short_version) repository, which removed face detecting and drop zone. After researching how to reduce the slug size, I noticed that changing `tensorflow` to `tensorflow-cpu` in the `requirements.txt` and removing all unnecessary packages and files helped a lot. However, even the webapp had a slug size of less than 500 MB; there were still many problems while deploying the app; for example, I found an error that said there was no such file by using view logs, but the webapp was working fine locally. Finally, I found out that I named some files which contained some capital letters. Furthermore, once I updated all file names to lowercase locally, the GitHub desk did not show any changes. I did not expect this much difficulty to develop on Heroku, so I am especially proud to build our webapp successfully.

## What are two things you would suggest doing to further improve your project?


1. Two days before our final presentation, I wanted to remove the background, cut out the dog from the image, and then display it with `Glassmorphism` effects inside the `Find Your Best Dog` page. However, it was impossible for me to do each image manually, so I wondered if there existed a model that would automatically remove a picture's background. Luckily, I found it is possible by using the `Image Segmentation` from TensorFlow. I would research more information about `image segmentation` and `object detection` if I had more time to improve our project.


2. I did not use any database for this project. I wish I could use the database to store and access all prediction results for all uploaded images.

## How does what you achieved compare to what you set out to do in your proposal? 


We achieved all planned deliverables in our [proposal](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/proposal.md), and I added more extra features to this project.
Since one of my group members successfully wrote a model to detect if an image contains any human face. So, I added some cool CSS effects. 

For example, dog breed prediction will be hidden when the model detects the uploaded image containing any human face. Then our web app will prompt the user that the uploaded picture might include humans.

<img src="/images/reflection_blog_ post_images/Face_detected1.png" alt="Face detected1 Image"> 

 Finally, the user needs to click the `Continue to show the prediction` button to see the predictions.

<img src="/images/reflection_blog_ post_images/Face_detected2.png" alt="Face detected2 Image"> 

## What are three things you learned from the experience of completing your project? 

1. I am still exploring GitHub; I had never used GitHub before this class. When I was thinking about displaying random images for each dog breed in the top three predictions, I learned that I could upload our dataset inside another repository and access all photos using the image URL. This method allows me to show multiple images for each dog breed without increasing slug size. I uploaded our training dataset inside the repository [pic16b-stanford-dog-dataset](https://github.com/PengWu2626/pic16b-stanford-dog-dataset). [Here](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/data/get_sample_images_path.ipynb) is the detail information about how I obtained all Image URLs.


2. I learned enough fundamental skills to build a simple interactive webapp using Flask. 


3. I learned how to use the TensorFlow package inside Flask locally on M1 Mac using Miniforge Environment. The instruction is inside the [README.md](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/README.md) file.

## How will your experience completing this project will help you in your future studies or career? 


The experience of building a project as a team is important for me.
Furthermore, I want to become a software engineer after I graduate; therefore, this hands-on project can better prepare me to fit in my future job environment. Before this class, I mainly practice many codes as a back-end developer. Therefore, I am grateful that this project let me practice many front-end skills, which I have always wanted to study.
