# Around SSR Challenge
**Table of Contents**

[TOCM]

[TOC]

## Instructions:
* Fork this repo,
* Check the description (se what we need bellow)
* Once you consider have a solution for the main problem, create a pull request to our `main` branch from your fork.
* Once we review your code we will notify you to have a feedback of your solution, please notify your submit to be able to review it ASAP.

## What do we need ?
![owen](https://owen-wilson-wow-api.herokuapp.com/static/media/Logo.3b55998c204f27064b30.png "owen")
We need to list a bunch of movies from the Owen Willson API  🎬
This is a public API,you don't require even an API key to fetch data from it, there some options to get this info, but **please just use this one**:
`https://owen-wilson-wow-api.herokuapp.com/wows/random?results=100`
*at the moment exist only 90 movies on this response*
we need to **display a list of these movies**, given some **parameters** in the request, example:
`/?minDate=2000&maxDate=2005&minDuration=60&maxDuration=120...`
the filters that **you should support are**:
- Word include in the name of the movie
- Year of the movie
- Duration of the movie
- number of wows in the movie

fell free to decide the name of these parameters

**all these parameters are optional**

these list **should be dispatch from the server**, but once it is** in the browser**, you should be able to filter it **from the original request** UI filter elements should be limited to the maximum and minimum values of the **original payload**,
if any parameter exist in the request it should be visible in the initial state of these filters.

## What will be evaluated ? 
*(sorted from main priority)*

Code **solution** of the main objective
**Simplicity** and readable code
**ES6+** Usage
Commit **history**
Time **spend**
**UI** generated
PR **structure**
