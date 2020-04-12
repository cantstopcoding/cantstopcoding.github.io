---
layout: post
title:      "My Tolstoy CLI Project "
date:       2020-04-12 02:39:06 +0000
permalink:  my_tolstoy_cli_project
---


I finally finished my CLI gem! It was definitely a challenging, but very fun process. I was really happy that I was able to work creatively on something. It took me a while to think about what to do the project on. I finally decided to create a project on books because I really love to read. I changed the website I would scrape multiple times because one had poor HTML structure, the other had a lot of javascript and was multiple levels deep. I wanted to keep things as simple as I could for my first project. The site I decided to scrape had an article called The 10 Books By Leo Tolstoy You Have To Read. It had decent HTML structure, and I was excited about the topic because Tolstoy is one of my favorite authors, if not my favorite author.

My vision for what my project would do in the end (which I actualized), was to provide the user Tolstoy's 10 must read books. The user will be asked to pick the number of the book he would like a summary of, or type "list" to see the books again, or type "exit" to leave. If anything else is typed, "Invalid Input" will be returned. After the summary, the list, or "Invalid Input" is returned, the user will be asked, again, what book summary he/she wants to see or to type list, or to exit. 

At first I worked on setting up my environment from scratch. I watched tutorials on how to set up my environment for the in browser on learn.co. I applied the logic of setting up my gem to my local environment on Visual Studio Code and learned how to push my code to Github.  Then I watched other turorials on CLI gem walktroughs and I made sure my bin/executable file was printing to the terminal. Next I created a CLI class and called it in my in my executable file to see if that worked. Once that worked I knew I didn't have to worry about the executable file anymore because everything that the user had to deal with would be encapsulated in the CLI.

I worked on my CLI class, wrote the code I wish I had, wrote fake data and tried to get my fake data working. When the oppourtunity gradually arose, I created a Book class, moved the fake data to the Book class and once I got the fake data to work with my CLI and the Book class and their relationship with each other, I replaced the fake data with the real data I scraped from the website. After I got that code to work I wanted to make a new class. My Book class scraped data from the website, created Book instances with that data and put the Book instance into the @@all array after the Book object was instantiated. I wanted to apply the Seperation of Concerns principal  and have my Book class only focus on creating Book instances and collecting those instances in the @@all array. So I created a Scraper class to strictly focus on scraping from the website and I made the Book class get the data from the Scraper class.

Next, I began working on refactoring my code. I think refactoring might be my favorite thing to do when coding, because I can focus on making all my messy code neat, simple and elegant. In refactoring, I also made sure to make my classes did not have circular dependencies. My Scraper class only knew about the data from the website and didn't know about my Book or CLI class; my Book class only depended on the Scraper class and didn' know about the CLI class; my CLI class only depended on my Book class and knew nothing about my Scraper class.

It was a very enjoyable project and I was thrilled to put my creative and logical skills to the test!

