---
layout: post
title: Let's make a full stack project FS101[1]
date: 2021-06-25
author: Gaurav
summary: Full Stack Development 1
categories: FS
thumbnail: heart
tags:
  - Full Stack Development
  - Web Application Development
  - FS101
---

## Introduction

I am going under training in Publicis Sapient and I have an amazing tutor [Vaibhav Vashishtha][4]. I am understanding new and quite a lot of things.

Even thought we are going to develop a full stack application but this FS101 series is going to act a exploring guide rather than a begineers tutorial. I will cover design process and code development but you have to create setups and learn every new word comes across you.

This is just a bridge between knowing how to code and developing a good full stack project.

Before building anything in real world, we need to know what are we building say bridge, building or boundary. So first of all we decide archetecture. Similarly here we are developing a web application. It must have some kind of archetecture. Let's see -

## Client Server Architecture

![Client Server architecture](/assets/images/client_server.jpg)

Above image shows a conventional sturucture of most web applications currently developed. In development we follow [Convention over configuration][1]. So you understand what we have on browser is client side and it's know as frontend. Backend is used to control main bussiness logic and whatever is served to client via http.

## MVC architecture

![MVC architecture](/assets/images/mvc.jpg)

You can observe this MVC archetecture as an expanded version of Client Server Archetecture. It definetly goes into details. View is what we present to client i.e. HTML page. Controller basically navigates user HTTP requests to corresponding bussiness logic. e.g www.facbook.com/login gets you to login page. Model is (the object) what carries the data behind backend. Basically it brings data from database and supplies it to View. You will get more clear about it as we go forward in the series.
That's your model view Controller - [MVC Archetecture][2].

## What are the options?

I have listed out a few options of programming laguages and frameworks used in development of full stack applications. There are 50+ possible combination, but it doesn't matter more than undestand the core concept of development.

![options for dev](/assets/images/option_mvc.jpg)

Thought tech stack depends on application we are building but as industy standard goes I will be using following tech stacks :

- Vue.js/React.js for Frontend
- RESTful API
- Java 11 with SpringBoot for Backend
- Postgressql as SQL database

If you know some of these, that's great. If you don't, Google tutorials are not that out of reach. I am kind of in between to follow testing along with development but we will see in upcoming blogs. But again remember the process will be same as explained in this [blog][3].

[1]: https://en.wikipedia.org/wiki/Convention_over_configuration
[2]: https://towardsdatascience.com/everything-you-need-to-know-about-mvc-architecture-3c827930b4c1
[3]: https://null-sys.github.io/fs/2021/06/17/diverse-field-of-web-app-development/
[4]: https://www.linkedin.com/in/vvashishtha/
