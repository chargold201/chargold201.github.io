---
layout: post
title:      "Sinatra Project - DiaBuddy"
date:       2019-08-20 12:32:37 +0000
permalink:  sinatra_project_-_diabuddy
---


As I have mentioned in a previous post, I have been a Type 1 Diabetic for most of my life (diagnosed at age 8). When I was a kid, I remember having to carry around a paper logbook where I would meticulously write down every blood sugar reading, insulin dose, meal, and notes such as whether I had been exercising or if I was sick... anything that could affect my blood sugar (and there are so many things that do!). For my Sinatra project, I decided to create a web application where users can keep track of all these things. No more paper and pens!

The application has two models, a User class and an Entry class. A User has many Entries. Each User has a name, email, and password digest, which the bcrypt gem uses to encrypt the user's password. Each Entry has the attributes of glucose, insulin, carbs, note, and user id. A user can sign up, log in, create, view, edit, and delete their own logbook entries. They are not able to change or view anyone else's entries.

The biggest challenge I had during this project was not technical, but personal. My grandmother has dementia, and I recieved a call that her situation was declining rapidly so I had to travel to North Carolina in order to spend time with her while I could. This meant that my project ended up being only MVP and not having the additional functionality I would have liked, but I do plan on expanding it in the future.
