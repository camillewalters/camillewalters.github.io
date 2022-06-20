+++
title = "Projects"
menu = "main"
+++

# fun stuff i'm working on

If you want to check out some of the code I've written, check out my [Github profile](https://github.com/camillewalters).

## Custom Smart Home System



## dotr
[Dotr](https://beadotr.com) is an experiment I did with NodeJS and Material AngularJS. I wanted to become more familiar with Node and Angular and I really liked the look of Material Design, so I started to work on Dotr. Dotr is a wishlist/wish-tracker for both gifters and gift receivers. The user enters Categories, Subcategories, and Items in order to keep track of things they or someone they know wants. To keep things interesting, every time you make an entry a google image search is done. The first result found is then proudly attached to your entry. This can have very unpredictable, and sometimes hysterical, results.

Dotr's backend is a RESTful api built in NodeJS using the Restify framework. The datestore is just a flat JSON file that is read from and written to. Eventually I'd like to move that to Redis. The frontend is Material AngularJS. It's served by an Nginx proxy in front of the node server.

## revolvingchore (deprecated)
[RevolvingChore(https://revolvingchore.com/) is a Ruby on Rails web app several friends and I built for a community college class we took recently. It is a chore chart tracker/generator application, created to make managing chores easier. We were living in a house with six guys, and chores were not always getting done. We attempted to print out a chore chart each month to tape to the fridge, but we often forgot. We knew it could be better, and much cooler, if it was an online application.

The user logs on with their Facebook account, creates a group, invites the other members of their house, and creates several chores. The app automatically assigns chores, cycles them, and sends reminders to do them. When a chore is completed, the users simply log on and mark it as completed. If a member of the group does not complete their chore by the end of the chore period, RevolvingChore will post a customized message on their Facebook wall. Accountability through public shaming! My favorite part of the app, however, is the plethora of interesting analytics we've added. I found a fantastic Javascript/HTML5 graphing library called [ChartJS](http://chartjs.org) which displays gorgeous, animated graphs. We have them all over the place on this app. We have charts showing which chores are most and least often completed, overall completion over time, who completes their chores the most and least often, and other fun pieces of information.

This app is running on my VPS, with Nginx, Thin, and a PostgreSQL backend. We deploy with Capistrano which, by the way, is completely incredible. We made a bit of an effort to write efficient code, so although my VPS is fairly minimalistic, this app is still quite speedy.

## net responsibility (deprecated)
[Net Responsibility](https://netresponsibility.com/) is an open source project I got involved in the summer of 2011.  It provides internet accountability software to users of Linux and OS X and soon, Windows.  I wrote some of the javascript functionality in the email report attachments and headed development and compatibility with OS X, including writing a launchd script to start the program on boot. I handle the majority of server setup and maintenance, as well as website & API improvements and bug fixes. My current and ongoing plans are to package this project for installation via Homebrew as well as to rewrite our web application and API using Yii 2.
