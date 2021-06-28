---
layout: post
title: Starting up - Requirement Analysis FS101[2]
date: 2021-06-25
author: Gaurav
summary: Full Stack Development 2
categories: FS
thumbnail: heart
tags:
  - Full Stack Development
  - Web Application Development
  - FS101
  - User Stories
  - Epics
---

## What are we developing?

My tutor [Vaibhav Vashishtha][4] came up with this great idea of a project which is concurrent and useful. He allowed me to use it for this series.

In simple term, the project is to develop a covid journal application where a patient can put his thoughts and vitals. It will be stored and shared.

Before we get started we need a tech savvy name for our application. I am thinking _Blaze Covid - A jouranl_. Now let's understand how to do a requirement analysis.

## How do we perform requirment analysis?

There are lot of methods to do requirment analysis but mostly [User stories][1] is the one being followed in [agile][2] projects. It simply goes in a hierarichal faishon like this -

![Epic archetecture](/assets/images/user-story.jpg)

There will be many epics and then each epic will be broken into user stories. Then each user stories will be broken into tasks and then we complete these tasks. But epics and user stories help us understand the user requirment from the application.

## Blaze Covid - A jouranl

Let's start with what user needs.

- Epic 1 : User login and registration with entry creation

  - User Story : As a user I can Login into the application
  - User Story : As a user I can Register to the application
  - User Story : As a user I can enter my vitals
  - User Story : As a user I can enter my thoughts and feelings as blog
    <br/><br/>

- Epic 2 : User can view and share his entry
  - User Story : As a user I can see all my entries
  - User Story : As a user I can see entries with specific #hashtag
  - User Story : As a user I can share my entry

Currently my needs are these and I will try to finish it. These may change along the way and so we will repeat the cycle in agile manner. But this is just what we understood from user. We don't know what are the technical requirements and design of the application. So now we move to the next phase of Design.

## Back to front development

I got acustomed to developing database, backend and then frontend. So I will be doing three [sprints][3]. One for database design, second for backend and the last one for forntend. Though sprints are meant to be done based on functional requirement. I am using here just as introduction.

- Sprint 1 : Database Development
- Sprint 2 : Backend Development
- Sprint 3 : Frontend Development

[1]: https://www.atlassian.com/agile/project-management/user-stories
[2]: https://www.atlassian.com/agile/manifesto
[3]: https://www.atlassian.com/agile/scrum/sprints
[4]: https://www.linkedin.com/in/vvashishtha/
