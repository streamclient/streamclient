# StreamViewer (SV)

## Introduction

In this coding assignment, you will be building a full-stack web application which will help its consumers view top ranked livestreams from Youtube, participate in the chat sessions and view historical chats and related statistics. Detailed specifications, related personas along with some other helpful information is provided below. Goodluck!


## How to approach this and logistics

You are not expected to (cumulatively) spend more than 8 hours on this task. These 8 hours can be spread over multiple days within a two week timeframe. You can start whenever you like. Please make reasonable assumptions and design choices where you feel the specification is unclear or falls short. Make sure to document your assumptions and design in the `README` or other relevant documents you produce (e.g. code comments).

To help you make these decisions, keep in mind that we ask candidates to complete these coding assignments in order to:

1. Gauge your technical strength and ability to work independently while delivering a feature complete product
2. Ability to navigate third-party interfaces (libraries/apis) where the documentation/spec might not be very detailed

All work you do will be your property; we are not trying to get free work done here. A couple hundred people have done this assignment previously (some are part of our team now!) and this functionality is live in our product(s).

We are expecting two things from you:
1. Link to live demo (heroku tends to be pretty easy/free and is used by most people)
2. Link to git repo (Github is a famous choice) consisting your source and `README`

Please note the following as well:
- Implmenting all functionality on the client side is prohibited
- You can use any language/framework for the backend _except_ NodeJS
- Please let us know your level of comfort with the language you choose to implement the backend so we try our best to evaluate your submission fairly
- The client appllication/frontend should be a _single_ `index.html` file linking to external CSS/JS (this also means you'll have to make a SPA). We like HTML5, CSS3 and Typescript, but you are not obliged to use them :)

## Personas
* Alex (viewer): Current visitor to the SV website and mostly uses Chrome on their desktop
* Natalie (streamer): Video game celeb who streams her sessions via Youtube live most days
* Kevin (super-mega-fan): A fan of Natalie who watches ALL of her streams and likes to chat while the streams run

## Requirements

1. Alex should be asked to login using his Google Account when he visits the SV website.
2. Alex should be presented with multiple livestreams to choose from on the `home` page. These are sourced from YT live api and selected/sorted based on logic you define
3. Alex should be able to click on a livestream to watch it
4. Alex should be able to see the associated chat session while watching Natalie's stream
5. Alex should be able to post messages to the chat session for the livestream he's viewing
6. All messages by Kevin to Natalie's livestream chat should be stored in a persistent storage
7. Alex should be able to visit the `stats` page
8. Alex should be able to search through all messages posted by Natalie's fans' usernames e.g. Kevin
9. Alex should be able to see a table with usernames, message count (plus any other stats you feel like). This table should be sortable.

## Bonus Requirements

10. The SV webapp is mobile responsive and setup as a PWA
11. The stats related to chat are summarized over a rolling time window (no. messages per X seconds)
12. The stats are sorted, refreshed and updated frequently (so we know who creates the most hype in chat sessions in almost realtime)


> Goodluck! And please feel free to ping us if you have any questions. We looking forward to having you on-board our team :)