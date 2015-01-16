# Github Notification Widget - [Übersicht](http://tracesof.net/uebersicht/)

Breakdown of GitHub Notifications by Type. For example the first category is mentioned, which will reflect how many notifications are due to you being specifically mentioned.

![Screenshot](https://github.com/mtscout6/uebersicht-github-notifications/raw/master/screenshot.png)

## Installation

Put the widget into the __Übersicht Widget folder__.

Create a [GitHub Auth Token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) with Notification Access.

![GitHub Auth Token Setup](http://cl.ly/image/1b2b3m0h3j2w/Image%202015-01-16%20at%208.30.36%20AM.png)

Configure the `user`, `apiKey`, and optional `enterpriseApi` and `enterprise` variables at the top of the `index.coffee` file.

To get both a public and enterpise notification bar, add two copies of the widget into the __Übersicht Widget folder__. Rename one of them, and configure each `index.coffee` for their respective public or enterprise target.

## Appearance

Change the location of the widgets by changing the first few lines of the `style` settings.
