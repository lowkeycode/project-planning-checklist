# Project Planning Checklist


## Prototype

* Use a design tool or hand draw a rough prototype outlining basic functionality & layout


## Build Set Up

* Determine the tech stack and necessary tooling for the project. (npm packages to be considered as needed)
* Scaffold file structure for html, css & js (or library/framework) files
* Set up & connect github/git repository


## Design System (CSS variables or other constants)

Determine:

* Colors (Main, Secondary, Tertiary, Greys, Whites) [Paletton](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF) [Colormind](http://colormind.io/) [0to255](https://www.0to255.com/)
* Typograpghy (Font-family, Font-size, Line Height, Letter Spacing) [Google Fonts](https://fonts.google.com/) [Type Scale](https://type-scale.com/)
* Padding/Margin
* Box Shadows(+ some other considerations if needed) [Developer Resources](https://rexwebmedia.hashnode.dev/resources-for-web-developers)
* Border Radiuses


## Layout

* Layout app/web page according to prototype with html & css as far as reasonable before adding javascript


## Images

* Stock Images [Unsplash](https://unsplash.com/)
* Take your own and edit with appropriate image maniuplation program
* Icons (Or build your own) [Flat Icon](https://www.flaticon.com/)


## User Stories

Describe the whole site or app functionality of all the types of users perspectives

* Use a visual tool for documentation [Miro](https://miro.com)
* As a (type of user), I want (an action) so that (a benefit)

## Features

List the required features to achieve each corresponding user story
![User Story/Features](https://github.com/lowkeycode/project-planning-checklist/blob/main/userStories-features.png)


## Flow Chart
Along-side the features create a flow chart for how the application should work (Add a legend for help)
![Legend](https://github.com/lowkeycode/project-planning-checklist/blob/main/legend.png)
![Flow Chart](https://github.com/lowkeycode/project-planning-checklist/blob/main/chart.png)

## Architecture

Not always necessary to start coding. Coding can help test some assumptions and architecture can be revisited.

Start thinking about different components and their requirements. Starting thinking about different styles (OOP/Funtional) and principles [SOLID](https://dev.to/francescoxx/solid-principles-in-javascript-3pek) what might fit well where.

Components Of Any Architecture:

1. Business Logic

* Code that solves the actual business problem
* Directly related to twhat the business does and what it needs
Ex.) WhatsApp (Sends messages), Bank App (Stores transaction records), Accounting Software (Calculates taxes)

2. State

* Stores all the data about the application (data from an API, data the user inputs, what page the suer is currently viewing etc.)
* Should be the "single source of truth"
* UI should be kept in sync with state
* There are state libraries (Redux, MobX)

3. HTTP Library
* Responsible for making and receiving AJAX requests
* Optional but almost always necessary in real-world apps

4. Application Logic (Router)
* Code that is only concerned about the implementation of the application itself
* Handles navigation on the page and UI events

5. Presentation Logic (UI Layer)
* Code that is concerned about the visible part of the application
* Essentially displays application state
* Keeps in sync with state



## Development

Go code.