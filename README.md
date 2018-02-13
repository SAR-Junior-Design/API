# API
This is the repository that has information on the API that the SAR-Drone project uses.


## Introduction

Let's start from the beginning. What is an API? The following video can explain a bit more, I'd highly recommend in case you are new to the subject: https://www.youtube.com/watch?v=s7wmiS2mSXY

How, in the modern world then, do we work on API's? What kind of tool makes debugging and building API tools easy? If only we had some kind of superhero...
Well it turns out we do! It's Postman! (https://www.getpostman.com/)

I would highly recommend learning postman if you want to use this project. In fact, the only files in this repository are generated by postman.

Okay, so you have an abstract understanding of what an API is, now what are we specifically doing? Or rather, what kind of API is in this repository?

## What is in this Repository

This repository describes a bunch of http requests that goes to our postgresql database. The database structure is described in an ER diagram (or at least one of those diagrams, I forgot some of that UML stuff) in this repository. The actual API is coded in the Application-Server repository, but here we have a postman file and environment file (one for production, and one for local if you set this stuff up locally).
