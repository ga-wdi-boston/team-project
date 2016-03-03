[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Building a SPA with an Express API with Your Team

## Required Reading

1.  [Group Guidelines](group-guidelines.md)
1.  [Working in Groups](group-work.md)
1.  [Group Roles](group-roles.md)

## Overview

You’ve already worked in small groups to accomplish various labs and exercises,
but this time **we’re going to challenge you to work on a whole project with a
small team.**

Not only will you be asked to **exercise additional creativity** in designing
your own project, your consultants will partner you with other classmates to
architect, design, and collaboratively build an API of your own design.

While your last project taught you how to get started with Ruby, SQL, and Ruby
on Rails, this project you'll be building something exciting with **Express and
Mongo.**

**This is meant to push you both technically and collaboratively.** It’s a lot
harder to work in a team than to work by yourself, but that's most likely
you’re going to find yourself doing in your first development job after WDI,
and **it's important to learn how to work together.**

Make it work, and make it awesome.

## Technical Requirements

Your app must:

-   **Use Mongo and Express** to build an API and a front-end that consumes it
-   **Create an API using at least 2 related models**, one of which should be a
    user
-   Include **all major CRUD functions** in a **RESTful API** for at least one
    of those models
-   **Consume your own API** by making your front-end with HTML, Javascript, and
    jQuery
-   **Add authentication to your API** to restrict access to appropriate users
-   **Craft thoughtful user stories together**, as a team
-   **Manage team contributions and collaboration** using a standard Git flow on
    Github
-   Layout and style your front-end with **clean and well-formatted CSS**
-   **Deploy your application online** so it's publicly accessible

## Necessary Deliverables

-   A **working API, built by the whole team**, hosted somewhere on the
    internet.
-   A **front-end app that consumes your API**, hosted somewhere on the
    internet.
-   **At least two Git repositories** (front-end and back-end) **hosted on
    Github**, with frequent commits from _every_ team member dating back to the
    _very beginning_ of the project.
-   The `README.md` file inside your _**front-end**_ repo should have:

    -   A short description of your application.
    -   A brief explanation of the **technologies** (Node modules, Express
        middleware etc) used.
    -   A couple of paragraphs detailing the **general approach you took**.
    -   Notes on any **unsolved problems** or **major hurdles** your team had to
        overcome.
    -   **Installation instructions** for any dependencies.
    -   A link to your **user stories** – who are your users, what do they want,
        and why?
    -   A link to your **ERD** - what data models does your app use?
    -   A link to your **wireframes** – sketches of major views / interfaces in
        your application.
    -   A link to the deployed front-end app.
    -   A link to the repo for your back-end.

-   The `README.md` file inside your _**back-end**_ repo should have:

    -   A short description of your application.
    -   A **catalog of routes (paths and methods)** that the API expects.
    -   A link to the deployed back-end app.
    -   A link to the repo for your front-end.

## The Prompts

Each team of students will be assigned one of the following projects to
complete. Though the broad brush-strokes are laid out for you here, the details
are up to you, so feel free to get as creative as you like!

Note: As in Project 2, _**only shoot for Reach Goals once you've satisfied the
core requirements**_.

### Bucketli.st

Besides finishing WDI, you surely have one or two things you'd love to do with
your life. Let's get 'em on paper! You could integrate with a third-party
location-based API to allow users to search for a location or venue to add to
their bucket list items.

**Reach Goal**: Add social features to your site, such as following other users.
Allow users to make certain list items public, but default to private.

### E-Commerce

Create an e-commerce site for famed retail giant, Nozama.com! Naturally, the
site will need to allow customers to see all of Nozama's products, add those
items to a shopping cart, and purchase them using
[Stripe](https://stripe.com/docs/checkout). In addition, by logging in,
customers should be able to keep track of their purchases by looking at their
past orders.

**Reach Goal**: Build a search feature so that people can search for specific
products by name.

### Survey

Make an app that can be used to create custom surveys (for instance, asking
"what should we eat for lunch today?" or "On a scale of 0-5, how well did you
understand what we just learned?") and collect the responses on a dashboard for
that particular survey. Each live survey should be hosted at a unique,
randomly-generated URL.

**Reach Goal**: Make the dashboard real-time, so you can see answers pour in as
they're completed.

### FileBucket

Build a Dropbox-like app that allows users to upload files into a virtual file
system. In addition to keeping track of file structure, this app should
associate meta-data with each file, including things like:

-   date created/uploaded
-   date modified
-   owner (person who uploaded the file)
-   tags

**Reach Goal**: Implement a simple permissions system for your CMS:

-   Ordinary users can only read/download a file.
-   Owners can do anything, and only owners can destroy or move a file.
-   'collaborators' can be chosen; they have permission to read from and write
    to files.

### Content Management System

Build an app to build a website! Your app must allow non-technical users to
write blog posts **and** pages for the site. When a visitor visits your site,
they should see content. When a user logs in, they should see a dashboard that
lets them create and edit new posts or pages.

**Reach Goal**: Implement authorization. Administrators should be able to delete
pages or posts, while normal users should be able to edit pages. Only
administrators can publish a new post, normal users can only save drafts.

## Overall Score

Your consultants will give you a total score on your project as an aggregate
across all feedback categories:

| Score | Expectations                                           |
|-------|--------------------------------------------------------|
| **0** | _Does not meet expectations._                          |
| **1** | _Meets expectations - good job!_                       |
| **2** | _Exceeds expectations, you magnificent creature, you!_ |

This will serve as a helpful overall gauge of whether you met the project goals.
But more important than your overall score is your feedback, particularly in
individual categories - this will help you identify where to focus your efforts
for future projects.

## Getting Started

Eager to get moving? Here are some good resources that you might want to refer
back to.

-   **[Express JS](http://expressjs.com/)**
-   **[MongoDB](https://www.mongodb.org/)**
-   **[Getting Starts with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)**

Some other suggestions and best practices:

-   **Don’t hesitate to write throwaway code** to solve short term problems.
-   **Read the docs for whatever technologies / frameworks / API’s you use**.
-   **Write your code DRY** and **build your APIs RESTful**.
-   **Be consistent with your code style.** You're working in teams, but you're
    only making one app per team. Make sure it looks like a unified effort.
-   **Commit early, commit often.** Don’t be afraid to break something because
    you can always go back in time to a previous version.
-   **Keep user stories small and well-defined**, and remember – user stories
    focus on what a user needs, not what development tasks need accomplishing.
-   **Write code another developer wouldn't have to ask you about**. Do your
    naming conventions make sense? Would another developer be able to look at
    your app and understand what everything is?
-   **Make it all well-formatted.** Are you indenting, consistently? Can we find
    the start and end of every div, curly brace, etc?
-   **Comment your code.** Will someone understand what is going on in each
    block or function? Even if it's obvious, explaining the what and why means
    someone else can pick it up and get it.
-   **Write pseudocode before you write actual code.** Thinking through the
    logic of something helps.
