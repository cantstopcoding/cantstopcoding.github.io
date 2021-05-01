---
layout: post
title:      "My React/Redux Project"
date:       2021-05-01 12:22:29 +0000
permalink:  my_react_redux_project
---


I finished my final project! It feels great and bizarre (in a good way) because I worked so hard for such a long time to get to this point. It was the most strenuous project yet and I had to make the call to wrap it up. I always want to go further but my goal is to find that balance of doing more without doing too much where I'm going to be stuck on something to the point of ridiculousness.

The most fun part of the project for me was refactoring. It feels nice to clean up all the messiness and get rid of the clutter. I find joy in making my code as efficient as possible and adhering to the DRY principle. However, I became a bit obsessive with drying my code up. For example, I wanted to extract every single one of my actions, but I felt I was compromising clarity. I did a bit of abstraction with my actions but I consciously chose to leave a bit of repetition. To be quite honest, I'm not sure how much abstraction is too much, but that's a general debate in software development. The amount of it is a very interesting debate that I would want to write a thesis about. But the most important thing is that if I'm asked to refactor more, I would feel comfortable doing so.

The most difficult thing about doing the application for me was extracting the forms. My account and item create forms looked very similar to the account and item edit forms. So when I initially created the refactored form, I ran into the problem of creating a new account or item on the edit forms. To solve this, I found some prop in the create form component that was not in the edit form. If that prop existed on submit (indicating it came from the create form), then I ran the create code, and if it didn't exist then I ran the edit form code.

I'm a much stronger person because of my experience at Flatiron. It brought out the best in me and forced me to face my demons and conquer them. I feel much more confident now that I got past all of these difficulties and I believe I can get past anything in life and work my way up to understanding and applying the most difficult of code!
