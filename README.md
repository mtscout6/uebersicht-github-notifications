# Github Notification Widgeth - [Übersicht](http://tracesof.net/uebersicht/)

Breakdown of GitHub Notifications by Type. For example the first category is mentioned, which will reflect how many notifications are due to you being specifically mentioned.

![Screenshot](http://cl.ly/image/3g3u372Z0r0U/Image%202015-01-16%20at%208.11.42%20AM.png)

## Installation

Put the widget into the __Übersicht Widget folder__.

Create a [GitHub Auth Token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) with Notification Access.

![GitHub Auth Token Setup](http://cl.ly/image/03073K3y162R/Image%202015-01-16%20at%208.20.50%20AM.png)

Configure the `user`, `apiKey`, and optional `enterpriseApi` and `enterprise` variables at the top of the `index.coffee` file.

To get both a public and enterpise notification bar, add two copies of the widget into the __Übersicht Widget folder__. Rename one of them, and configure each `index.coffee` for their respective public or enterprise target.

## Appearance

Change the location of the widgets by changing the first few lines of the `style` settings.
