---
layout: project
title:  "SlyDv"
subtitle:  "Presentation slides for developers"
permalink: /projects/slydv
tags: Deque Cauldron, eslint-config-airbnb, Express, jsx-a11y, Marked, Node, Postgres, React, react-document-title, Redux, Runkit, Sequelize, Socket.io
---

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/8gZyN4T3C9A?rel=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>

*[REPL]: read-eval-print loop

SlyDv was an itch-scratching project. At Grace Hopper, we saw—and gave—a lot of presentations where the speaker had to switch to a REPL to demonstrate some code, and then fumbled around to find the slides again afterward. We also saw a lot of people fussing more about their slide layouts than about the content itself. So we wanted to develop a presentation app that let you create vanilla slides using Markdown, and also make REPL slides that could be prepopulated with code and then live-edited and run while presenting.

In three weeks, we met these goals and also added a remote-control page that presenters can use on their phones, a style switcher for the slide decks, and a text chat interface for the audience and presenter to communicate through. And we used Deque Labs’s Cauldron library and jsx-a11y to help make the forms and controls accessible.

## Team members

-   India Amos
-   Alice Chuang
-   Georgina Hoagland
-   Leigh Steiner

## Key contributions

-   Designed the application flow around slide editing 
-   Specified and designed the slide template types
-   Built and styled the slide editing form
-   Added confirmation popups to prevent accidental data loss, and tooltips to improve ease of use
-   Set up descriptive page titles on each component to make it easier to use the browser’s back and forward buttons with this single-page application
-   Evangelized for use of the Airbnb linter
-   Kept our issue list up to date and comprehensible

## Links

-   [Code](https://github.com/EvilDeds/slydv)
-   [Demo](http://www.slydv.tech/)
