---
layout: post
title: Database Design and Development FS101[3]
date: 2021-06-27
author: Gaurav
summary: Full Stack Development 3
categories: FS
thumbnail: heart
tags:
  - Full Stack Development
  - Web Application Development
  - FS101
  - Database
  - SQL
---

## Introduction

I am compressing database design and development into one phase,since after designing database, implementation is quite easy due to GUI based interfaces. I will be using following tools

1. [draw.io][1] for ER Diagrams
2. [Postgresql][2] with pgAdmin4 as Database

Before we go ahead, there are many choices available with each development steps and as a developer you have to make those decisions. They might be wrong, but it is a learning process.

## Entity Relation Diagram

ER Diagram basically tells us about the entities and their relationship. Layman can say Entites are table and relationships are foreign keys. But it's not so simple after all. Before moving ahead I assume that you understand ER Diagram, Table, Keys and DB Normalization Forms (upto 3NF). Basic DBMS courses will have these or you can google.

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

[1]: https://app.diagrams.net/
[2]: https://www.postgresql.org/download/
[3]: https://www.atlassian.com/agile/scrum/sprints
