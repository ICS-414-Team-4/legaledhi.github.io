# Legal ED HI

## Table of contents

* [Overview](#overview)
* [Mockup Pages](coming soon)
* [Deployment](coming soon)
* [User Guide](coming soon)
* [Developer Guide](coming soon)
* [Development History](coming soon)
* [Continuous Integration](coming soon)
* [Team](#team)

## Overview

The purpose of this project is to provide a tool for the Hawaii Department of Education that facilitates the passing of state legislature.

Some of the main functions of this tool will be:

* To provide real-time tracking of legislative measures.
* Notifying the relevant people/offices when action from them must be taken.
* Automating tasks such as document creation and updating.
* Provide the ability to search measures by key parameters and keywords.
* Track changes to documents and allow for easy comparison of different versions.

This application will help to streamline the legislative process and prevent measures from accidentally being retired due to disorganization or miscommunication.


## Mockup Pages

This section provides a walkthrough of the Bowfolios user interface and its capabilities.

### Landing Page

The landing page is presented to users when they visit the top-level URL to the site.

![](images/landing-page.png)

### Index pages (Projects, Profiles, Interests)

Bowfolios provides three public pages that present the contents of the database organized in various ways.

The Profiles page shows all the current defined profiles and their associated Projects and Interests:

![](images/profiles-page.png)

The Projects page shows all the currently defined Projects and their associated Profiles and Interests:

![](images/projects-page.png)

Finally, the Interests page shows all the currently defined Interests, and their associated Profiles and Projects:

![](images/interests-page.png)

### Home page

After logging in, you are taken to the home page, which presents a form where you can complete and/or update your personal profile:

![](images/home-page.png)

### Add Project page

Once you are logged in, you can define new projects with the Add Project page:

![](images/add-project-page.png)

## Development History

The development process for BowFolios conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

The following sections document the development history of BowFolios.

### Milestone 1: Mockup development

The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system.

Milestone 1 was managed using [BowFolio GitHub Project Board M1](https://github.com/bowfolios/bowfolios/projects/1):

![](images/project-board-1.png)

### Milestone 2: Data model development

The goal of Milestone 2 was to implement the data model: the underlying set of Mongo Collections and the operations upon them that would support the BowFolio application.

Milestone 2 was managed using [BowFolio GitHub Project Board M2](https://github.com/bowfolios/bowfolios/projects/2):

![](images/project-board-2.png)

## Milestone 3: Final touches

The goal of Milestone 3 was to clean up the code base and fix minor UI issues.

Milestone 3 was managed using [BowFolio GitHub Project Board M3](https://github.com/bowfolios/bowfolios/projects/3):

![](images/project-board-3.png)

As of the time of writing, this screenshot shows that there is an ongoing task (i.e. this writing).

## Walkthrough videos

BowFolios is intended as a model of how an ICS 314 project could be organized and executed. Here are videos that walk you through various aspects of the system:

* [BowFolios Part 1: Application Overview (5 min)](https://www.youtube.com/watch?v=5lXSLf9VHqw)
* [BowFolios Part 2: Application Structure and Control Flow (14 min)](https://www.youtube.com/watch?v=hQYc8UK4K7w)
* [BowFolios Part 3: Data Model, Data Initialization, Publications and Subscriptions (27 min)](https://www.youtube.com/watch?v=pcZg_44Ssdk)
* [BowFolios Part 4: Forms and Meteor Methods (20 min)](https://www.youtube.com/watch?v=TLavamIYaEc)
* [BowFolios Part 5: Loading data using Assets (8 min)](https://www.youtube.com/watch?v=NzrTzBPCJPo)
* [BowFolios Part 6: End-to-End testing in BowFolios (24 min)](https://www.youtube.com/watch?v=B8TSiCLBeaA)

## Team

BowFolios is designed, implemented, and maintained by [Philip Johnson](https://philipmjohnson.org) and [Cam Moore](https://cammoore.github.io/).
