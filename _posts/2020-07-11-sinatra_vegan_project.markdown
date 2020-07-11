---
layout: post
title:      "Sinatra Vegan Project"
date:       2020-07-11 23:57:51 +0000
permalink:  sinatra_vegan_project
---


When I first started my project I had no I idea what I wanted to do. It took me a bit of time to figure it out, but I decided that it will be a web app that will have a user be able to post vegan recipes. I'm glad I did this project because I was able to get a great understanding about how the models, views and controllers interact with each other, as well as their functions. 

For the project, I only had to create CRUD routes for my belongs_to resource. I did that but I still felt a little shaky with enacting CRUD and I wanted to get a better understanding of restful routes and working with MVCs. For this reason I decided to not only to perform CRUD actions for my belongs_to resource (recipes), but I decided to do CRUD routes on my has_many resource (user) as well. That really helped me because I got more repetition in the struggle and when you do more reps, you get stronger at something. 

One of the biggest struggles I had was ensuring that someone could not go to another person's user page and edit it. What I did to solve this issue was create an authorized_to_edit_user? helper method, in the application controller. The method is a boolean that returns true if the session id is equal to the params id and false if it is not. In the '/users/:id/edit', in the users controller, I made the condition so that the user was authorized_to_edit user then he can see the users/edit page otherwise the individual who is trying to hack will be redirected to the home page with a flash message that they are not authorized to update that user. To add an extra layer of security, if the person wasn't authorized_to_edit_user?, I hid the button from them on the view page. 

I felt proud that I solved that problem but my favorite thing about this project is that I was actually able to make an application on the browser. In my last project, I created an app and although it was cool that I created something on the command line, it is way cooler to make an application on the web browser. To me, it is more aesthetically pleasing to the eye. I know that this project is low level but knowing that I made a website is very cool and I'm really looking forward what's to come!

I'm excited to move on to Ruby on Rails and seeing how everything I learned will get abstracted away so I can focus less on tedious stuff. One of things I appreciate most about attending Flatiron is to learn the minutiae of something and have everything I worked so hard on get abstracted, so I can really have a strong fundamental understanding of what is going on above and under the surface. I don't want Ruby on Rails or any future language I use to seem like magic to me because of abstraction.
