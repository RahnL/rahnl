---
layout: post
title: Finding a person - A look at building a person searching algorithm
date: 2013-11-14 21:57
author: Rahn
comments: true
categories: [.Net, Algorithm, presentation, Technology, Training]
---
I did a presentation for the <a href="http://www.meetup.com/Gwinnett-Microsoft-Users-Group/events/146643472/">Gwinnett Microsoft Users Group</a> on finding a person and building a custom algorithm to match incoming data to existing data.

Attached is my slide presentation. <a href="http://gonesomewhere.com/wp-content/uploads/2013/11/Finding-a-Person.pptx">Finding a Person</a>

The sample code I presented is on Github:  <a href="https://github.com/RahnL/FindPersonDemo">https://github.com/RahnL/FindPersonDemo</a>

Thanks for allowing me to speak. I had a great time and I appreciate the questions and feedback I got.

For me to followup on:

- Are datasets slowing me down? Should I store data some other way after I get it out of the database that provides better performance?

- Is it worth broadening my returned data, and paring it down in memory instead of doing repeated queries?

- Would it work to hash  the data, and search through the hashes? Would that be any faster?  Given what that would take, might it be better to move to a NoSQL db, as I've been contemplating?

- A note of clarification.  On the records I receive (200-250K a day), a good number of them are throw out before they get to the point of hitting the person search process.

- Thanks for the other feedback and questions.
