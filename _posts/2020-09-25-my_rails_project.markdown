---
layout: post
title:      "My Rails Project"
date:       2020-09-26 02:10:53 +0000
permalink:  my_rails_project
---


I finally finished my Rails project! It took a long time to finish because I took my time to digest things. I try to strike a balance at Flatiron: taking my time to really learn and have the curriculum sink in (so coding becomes as instinctual as possible for me before I start my career) and moving things along so I don't get stuck and take forever on something, knowing I have a whole career to master whatever it is I may be fixated on. That balance brings about mixed feelings, but in the big picture, taking a little longer is making me a better developer. 

My Rails project is a website I want to build for my friend who makes costumes. My goal was to build an app for her after graduating from Flatiron but I said to myself, "why not just start the site now?" This way, when I finish school, I will get a lot of heavy lifting out of the way and I can focus on the much more innovative features that we both envisioned.

For now, the application is focused on the administrator side of things. My friend will be the only admin but I made it as if there were multiple admins (the project is also open to expansion). The website will allow for users to be able to post items they want to sell, or display it for their portfolio, and the user has the option to write blog content for that post. Other users can comment on the item. Later on, I plan to separate items and blogs, comments and reviews and basic user authorization and administrator authorization. 

My favorite part about the project was the abstraction. I took a shot at metaprogramming and made it work. I abstracted helper methods that I used in different controllers, but were the same pattern, and put it in the application controller. I set the dynamic instance variable using the instance_variable_get method. I definitely want to utilize metaprogramming more. I'm fascinated with it and it looks super elegant to me, even though I certainly did not master it and probably did not make my metaprogramming look the prettiest. I look forward on practicing it more, it was super fun!

My biggest struggle by far was dealing with nested resources. The difficulty was a number of things, such as, how to associate the nested resource to the parent resource when the child is created; when to use it in the controllers; how to indicate it's a nested route in the controllers, in addition to many other things. I just have to keep practicing to get used to it. Despite nesting and many other things being very demanding, I enjoyed the challenge.

The projects are my favorite part of the curriculum because that is where everything I've learned in the module comes together. In the modules, before I build the apps, it feels like a struggle, but when I do the projects, I have a lot of light bulb moments, and this was certainly true for my Rails application. Although initially, I'm uncomfortable with every new project, I get more comfort in the discomfort. I know there can't be growth without feeling vulnerable.



 
