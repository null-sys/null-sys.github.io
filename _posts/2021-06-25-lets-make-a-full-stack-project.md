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

Even though we are going to develop a full stack application but this FS101 series is going to act as an exploring guide rather than a beginners tutorial. I will cover the design process and code development but you have to create setups and learn every new word that comes across you.

This is just a bridge between knowing how to code and developing a good full stack project.

Before building anything in the real world, we need to know what are we building say bridge, building, or boundary. So, first of all, we decide on architecture. Similarly here we are developing a web application. It must have some kind of architecture. Let's see -

## Client-Server Architecture

![Client Server architecture](/assets/images/client_server.jpg)

The above image shows the conventional structure of most web applications currently developed. In development, we follow [Convention over configuration][1]. So you understand what we have on the browser is client-side and it's known as frontend. Backend is used to control main business logic and whatever is served to the client via HTTP.

## MVC architecture

![MVC architecture](/assets/images/mvc.jpg)

You can observe this MVC architecture as an expanded version of Client-Server Architecture. It goes into detail. The view is what we present to the client i.e. HTML page. The controller navigates user HTTP requests to corresponding business logic. e.g www.facbook.com/login gets you to the login page. Model is (the object) that carries the data behind the backend. It brings data from the database and supplies it to View. You will get more clear about it as we go forward in the series.
That's your model view Controller - [MVC Architecture][2].

## What are the options?

I have listed out a few options of programming languages and frameworks used in the development of full stack applications. There are 50+ possible combinations, but it doesn't matter more than undestanding the core concept of development.

![options for dev](/assets/images/option_mvc.jpg)

Thought tech stack depends on the application we are building but as industry-standard goes, I will be using the following tech stacks :

- Vue.js/React.js for Frontend
- RESTful API
- Java 11 with SpringBoot for Backend
- PostgreSQL as SQL database

If you know some of these, that's great. If you don't, Google tutorials are not that out of reach. I am kind of in-between to follow testing along with development but we will see in upcoming blogs. But again remember the process will be the same as explained in this [blog][3].

[1]: https://en.wikipedia.org/wiki/Convention_over_configuration
[2]: https://towardsdatascience.com/everything-you-need-to-know-about-mvc-architecture-3c827930b4c1
[3]: https://null-sys.github.io/fs/2021/06/17/diverse-field-of-web-app-development/
[4]: https://www.linkedin.com/in/vvashishtha/
