# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #3: Building An API Using Express

## Required Reading

1. [Group Guidelines](group-guidelines.md)
1. [Group Roles](group-roles.md)

## Overview

You’ve already worked in small groups to accomplish various labs and exercises, but this time **we’re going to challenge you to work on a whole project with a small team.**

Not only will you be asked to **exercise additional creativity** in designing your own project, your instructors will partner you with other classmates to architect, design, and collaboratively build an API of your own design.

While your last project taught you how to get started with Ruby, SQL, & Ruby on Rails, this project you'll be building something exciting with **Express & Mongo.**

**This is meant to push you both technically and collaboratively.** It’s a lot harder to work in a team than to work by yourself, but that's most likely you’re going to find yourself doing in your first development job after WDI, and **it's important to learn how to work together.**

Make it work, and make it awesome.

## Technical Requirements

Your app must:

* **Use Mongo & Express** to build an API and a front-end that consumes it
* **Create an API using at least 2 related models**, one of which should be a user
* Include **all major CRUD functions** in a **RESTful API** for at least one of those models
* **Consume your own API** by making your front-end with HTML, Javascript, & jQuery
* **Add authentication to your API** to restrict access to appropriate users
* **Craft thoughtful user stories together**, as a team
* **Manage team contributions and collaboration** using a standard Git flow on Github
* Layout and style your front-end with **clean & well-formatted CSS**
* **Deploy your application online** so it's publicly accessible

## Necessary Deliverables

* A **working API, built by the whole team**, hosted somewhere on the internet.
* A **front-end app that consumes your API**, hosted somewhere on the internet.
* **At least two Git repositories** (front-end and back-end) **hosted on Github**, with frequent commits from _every_ team member dating back to the _very beginning_ of the project.
* The `README.md` file inside your _**front-end**_ repo should have:
    * A short description of your application.
    * A brief explanation of the **technologies** (Node modules, Express middleware etc) used.
    * A couple of paragraphs detailing the **general approach you took**.
    * Notes on any **unsolved problems** or **major hurdles** your team had to overcome.
    * **Installation instructions** for any dependencies.
    * A link to your **user stories** – who are your users, what do they want, and why?
    * A link to your **ERD** - what data models does your app use?
    * A link to your **wireframes** – sketches of major views / interfaces in your application.
    * A link to the deployed front-end app.
    * A link to the repo for your back-end.
* The `README.md` file inside your _**back-end**_ repo should have:
    * A short description of your application.
    * A **catalog of routes (paths and methods)** that the API expects.
    * A link to the deployed back-end app.
    * A link to the repo for your front-end.

## Getting Started

Eager to get moving? Here are some good resources that you might want to refer back to.

* **[Express JS](http://expressjs.com/)**
* **[Sequelize](http://docs.sequelizejs.com/en/latest/)**
* **[MongoDB](https://www.mongodb.org/)**
* **[Getting Starts with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)**

Some other suggestions and best practices:

* **Don’t hesitate to write throwaway code** to solve short term problems.
* **Read the docs for whatever technologies / frameworks / API’s you use**.
* **Write your code DRY** and **build your APIs RESTful**.
* **Be consistent with your code style.** You're working in teams, but you're only making one app per team. Make sure it looks like a unified effort.
* **Commit early, commit often.** Don’t be afraid to break something because you can always go back in time to a previous version.
* **Keep user stories small and well-defined**, and remember – user stories focus on what a user needs, not what development tasks need accomplishing.
* **Write code another developer wouldn't have to ask you about**. Do your naming conventions make sense? Would another developer be able to look at your app and understand what everything is?
* **Make it all well-formatted.** Are you indenting, consistently? Can we find the start and end of every div, curly brace, etc?
* **Comment your code.** Will someone understand what is going on in each block or function? Even if it's obvious, explaining the what & why means someone else can pick it up and get it.
* **Write pseudocode before you write actual code.** Thinking through the logic of something helps.

# The Prompts

Each team of students will be assigned one of the following projects to complete. Though the broad brush-strokes are laid out for you here, the details are up to you, so feel free to get as creative as you like!

Note: As in Project 2, _**only shoot for Reach Goals once you've satisfied the core requirements**_.

## Bucketli.st
Besides finishing WDI, you surely have one or two things you'd love to do with your life. Let's get 'em on paper! You could integrate with a third-party location-based API to allow users to search for a location or venue to add to their bucket list items.

**Reach Goal**: Add social features to your site, such as following other users. Allow users to make certain list items public, but default to private.

## E-Commerce
Create an e-commerce site for famed retail giant, Nozama.com! Naturally, the site will need to allow customers to see all of Nozama's products, add those items to a shopping cart, and purchase them using [Stripe](https://stripe.com/docs/checkout). In addition, by logging in, customers should be able to keep track of their purchases by looking at their past orders.

**Reach Goal**: Build a search feature so that people can search for specific products by name.

## Survey
Make an app that can be used to create custom surveys (for instance, asking "what should we eat for lunch today?" or "On a scale of 0-5, how well did you understand what we just learned?") and collect the responses on a dashboard for that particular survey. Each live survey should be hosted at a unique, randomly-generated URL.

**Reach Goal**: Make the dashboard real-time, so you can see answers pour in as they're completed.

## FileBucket

Build a Dropbox-like app that allows users to upload files into a virtual file system. In addition to keeping track of file structure, this app should associate meta-data with each file, including things like:

- date created/uploaded
- date modified
- owner (person who uploaded the file)
- tags

**Reach Goal**: Implement a simple permissions system for your CMS:

- Ordinary users can only read/download a file.
- Owners can do anything, and only owners can destroy or move a file.
- 'collaborators' can be chosen; they have permission to read from and write to files.

## Content Management System

Build an app to build a website! Your app must allow non-technical users to write blog posts **and** pages for the site. When a visitor visits your site, they should see content. When a user logs in, they should see a dashboard that lets them create and edit new posts or pages.

**Reach Goal**: Implement authorization. Administrators should be able to delete pages or posts, while normal users should be able to edit pages. Only administrators can publish a new post, normal users can only save drafts.

---

# Feedback

Your instructors will give you a total score on your project as an aggregate across all feedback categories:

  Score | Expectations
  ----- | ------------
  **0** | _Does not meet expectations._
  **1** | _Meets expectations - good job!_
  **2** | _Exceeds expectations, you magnificent creature, you!_

This will serve as a helpful overall gauge of whether you met the project goals. But more important than your overall score is your feedback, particularly in individual categories - this will help you identify where to focus your efforts for future projects.

Below are specifics on each category, along with examples of what `0`, `1`, or `2` might look like.

## Workflow

### __Planning__

Did you create user stories, wireframes, and an ERD before you started writing code? Did you create (and follow) a schedule for your team to keep the project on track?

| Score | Description |
|:-----:|:------------|
| 0 | No planning documents present. |
| 1 | Basic planning documents (wireframes, simple user stories, and rough data model) |
| 2 | Clear, detailed planning materials that make it easy for someone to follow the entire flow of the project. Professional-level planning. |

### __Source Control__

Did your team use source control effectively to manage everyones' contributions and keep track of changes?

| Score | Description |
|:-----:|:------------|
| 0 | Large, infrequent commits containing work on multiple disparate features. Merge conflicts were common and involved significant rewrites. |
| 1 | Small, regular commits that reasonably divide up the work that was done. Effective use of branching to divvy up responsibilities. Occasional merge conflicts, but fairly small and resolvable. |
| 2 | Sophisticated use of branching and merging for managing different features. Merge conflicts were minimal to non-existent. |

### __Teamwork__

Did your group work together effectively?

| Score | Description |
|:-----:|:------------|
| 0 | Communication breakdowns. Flaring tempers. You know it when you see it. |
| 1 | Occasional disagreements, but for the most part the team worked together effectively. Reasonable intra-group communication. |
| 2 | High-performing team. Members of this group worked together very effectively - clear communication, cohesive group dynamic, etc. |

### __Group Contribution__

Did you personally contribute in a meaningful way to your group's project?

| Score | Description |
|:-----:|:------------|
| 0 | Only contributed superficially to the project; did not stay on top of group responsibilities. |
| 1 | Contributed meaningfully to the group. Generally kept on top of group responsibilities. |
| 2 | Played a major role in moving the project forward, building cohesion within the team, and keeping the team on task. |

## Deliverables

### __Technical Requirements__

Does your project meet all the technical requirements outlined above? Does it run?

| Score | Description |
|:-----:|:------------|
| 0 | App does not run on localhost, or runs but is missing significant features specified above. |
| 1 | App meets most core requirements and, the back-end has been deployed (in some form) to Heroku. |
| 2 | App meets **all** core requirements _and_ achieves some stretch goals. |

### __Software Design/Problem Solving__

How did you break up the functionality of your application? Do the solutions you came up with make sense, from the perspective of industry best practices? How well can you defend the choices you've made?

| Score | Description |
|:-----:|:------------|
| 0 | Little to no separation of concerns on the front-end. Poor choice of models and model relationships on the back-end. |
| 1 | Some separation of concerns on the front-end. Reasonable choices of models and relationships. |
| 2 | Clear separation of concerns on the front-end. Data models and model relationships are well-chosen for the problem at hand. |

### __Code Clarity__

Did you follow code style guidance and best practices covered in class, such as spacing and semantic naming? Did you comment your code as your instructors have in class?

| Score | Description |
|:-----:|:------------|
| 0 | Lots of missing semicolons in the JavaScript. Poor variable naming. Improper indenting _anywhere_. Excessive comments in the finished app. |
| 1 | Code is semantically correct. Naming isn't great, but is reasonable. Small number of select comments. |
| 2 | Code is extremely readable. Comments may be present, but are almost unnecessary because of how clear the code is. |

### __Creativity__

Did you add a personal spin or creative element into your project submission? Is the finished product something of value to the end user, in addition to being functional (not just a login button and an index page)?

| Score | Description |
|:-----:|:------------|
| 0 | App is very basic, and features very little creativity. |
| 1 | App shows some originality and inventiveness. |
| 2 | App is very novel because of its (a) approach, (b) UI, or (c) some other factor. |


