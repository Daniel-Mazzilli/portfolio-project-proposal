# Module 4 Portfolio Project Proposal

## Overview

We will soon introduce the requirements for your _Personal Portfolio Project_.

Much like in Module 2, you will have the freedom to choose the topic for your application.

This time, you'll create a **Full Stack Application** using the PERN stack.


This proposal will serve as a starting point for your ideas and plans.

\*\* **You must submit a proposal and receive approval from an instructor prior to working on your project.**

## Proposal Requirements:

The following requirements must be included in your proposal:

1. **Topic/Idea** -- can be a title w/ a short description

1. **3 User Stories** minimum, describing what a user can expect to see/do when using your application

1. **Wireframes** -- a lo-fidelity visual representation of your front-end using whatever tools you choose. (even pencil and paper)

1. **ERD** for your back-end. Only **one** table is required, but you must add all columns that are expected for each entry to your table(what info does an entry have?)
_For example: a user may have id, name, email, phone_

Your proposal is to be submitted AFTER the Portfolio Project Requirements and Repo have been shared with you in class. 

Please submit your proposal in a **group message with JD && Carlos** via Slack.

## Proposal:
**Topic/Idea** -- A travel journal/diary app. I am studying how to implement React Simple Map, and a geocoding API. Ideally I would like to have a world map with markers and annotation linked to countries/cities visited.
**3 User Stories** --  As a user you start by signing up or logging into your profile. As a user you may visit an index page with a list of trips linked to your account. As a user you may visit a more detailed show page for a specifi trip. As a user you may add/edit/delete trips.
**Wireframes** -- 
**ERD** -- users -> id SERIAL PRIMARY KEY, fullName TEXT NOT NULL, email TEXT NOT NULL, username TEXT NOT NULL, password TEXT NOT NULL // trips -> id SERIAL PRIMARY KEY, location TEXT NOT NULL, descriptin TEXT, travelCompanions TEXT, favoriteMeal TEXT, is_favorite BOOL, user_id INTEGER REFERENCES users (id) ON DELETE CASCADE
This is the general idea for the DB, will add more fields. Maybe more tables.
