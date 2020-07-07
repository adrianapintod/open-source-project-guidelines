# open-source project guidelines

Set of guidelines to create open-source projects from scratch.

# Goal of this Guidebook

As the organizational team of the 2020 open-source software project of Free University Berlin we strived to create ideas on how best to develop a decentralized project.

# Organization of a team

Very much in the beginning we started with a subdivision of all developers into smaller project teams. An organizational team is necessary to keep an overview and coordinate tasks.

### weekly meetings

A weekly standup was used to coordinate activities, and plan tasks for the following week.
Big Blue Button performed well for this task, especially because of the ability to form breakout rooms.
A great generator for Stand-up-Questions can be found [here](http://checkin.daresay.io/).
We named tasks bounties, more detailed information about our workflow propositions can be found in the Contribution document. In the weekly meeting all tasks for the upcoming week should be created and discussed.

### expert meetings

To further coordination of the project we introduced expert meeting at a half way point where one person of each group would attend to help increase inter-team communication and a sense of responsibility for the group as a whole.

### Kanban boards

Kanban boards are a useful tool to order tasks by teams, an explanation can be found [here](https://github.com/adrianapintod/open-source-project-guidelines/wiki/Kanban)

### Development tools

An overview over useful development tools can be found [here](https://github.com/adrianapintod/open-source-project-guidelines/wiki/Development-tools).

# GitHub features

## Issues / Bounties

Issues are central to GitHub and should be central to the work of your team. Every task should be documented as an Issue with a primary worker assigned and to be reviewed by an independent person. Our workflow around contributions is detailed [here](https://github.com/adrianapintod/open-source-project-guidelines/blob/master/CONTRIBUTION.md).

### Rating of work

We used a Fibonacci scale to rate work as the precision in time estimation drops with a higher time.
Therefore we created labels using a T-shirt sized rating system, described more in detail in the Contribution document.

- size-XXS: 2h
- size-XS: 3h
- size-S: 5h
- size-M: 8h

## Pull Requests

Code and other additions should not be pushed directly to the master branch but rather contributed to a forked repository or a feature branch to than be merged back into the project.

## Wiki

The Wiki is an easy way to add documentation to a project, it is a separately version controlled repository which can be cloned by adding a `wiki.git` ending. To clone the wiki of this git you would have to do the following: `git clone git@github.com:FUB-HCC/20-SWP-CodingOpenness.wiki.git`.
[This](https://github.com/adriantanasa/github-wiki-sidebar) nifty tool helps with creating a simple menu.

## Templates

GitHub allows the creation of templates for Issues and Pull Requests which simplify the workflow while guaranteeing the adherence to the Contribution guidelines. To be found in this repository are:

- Issue-Template
- Pull-Request-Template

# Code of Conduct

We believe that every team needs a good work climate, therefore we included a recommended Code of Conduct.
