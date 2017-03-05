# Node.js API Training

Welcome! This short training course will take you through the steps needed to build a Web API in Node.js. This course is intended for beginners to Node.js who ideally have some API programming experience in other languages and frameworks.

The training component of this course has been delegated to this excellent [Udemy course on Node.js](https://www.udemy.com/the-complete-nodejs-developer-course-2). If you're new to JavaScript, you can check out some of [these courses](https://www.udemy.com/courses/search/?q=javascript).

The remaining content involves building a practical application with the skills you learn in the Node.js course above. The aim is to go as far as possible with the exercise and work things out as you go. If you get stuck, follow the usual software engineering procedure:

1. Ask yourself why it's not working.
2. Check the obvious solutions.
3. Google the problem and possible solutions.
4. Ask for help from peers and mentors.
5. See step 1.

## The Problem

A real estate company needs an API which allows users to browse housing property listings for sale and rent. This API will be used for their website and mobile apps to support customers, agents, and admins.

We must use the [Zoopla Property Listings API](http://developer.zoopla.com/docs/read/Property_listings\) to populate housing properties into our own API. In order to use the API freely, you must [register an account]\(http://developer.zoopla.com/member/register\). Due to the API request restrictions and for the purposes of testing, feel free to use this [mock server]\(https://github.com/aramk/zoopla-api-mock) to populate our own data modals.

The API should support:

* RESTful CRUD actions \(Create, Read, Update, Delete\) on properties.
* An action to trigger importing from Zoopla given a set of parameters.
* Persistence of data models with MongoDB.

The architecture should be separated into three layers:

* property-listing-models



