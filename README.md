# GBIF.org feedback
This repository is used by [GBIF.org](http://gbif.org) as users generate issues via the website.
From here issues should be copied to their relevant projects (e.g. [checklistbank](https://github.com/gbif/checklistbank)) and then closed.
Content issues and helpdesk questions stay in this repository until addressed.

_It is our goal that issues in this repository are addressed and closed and no issues remain open._

## Flow

The user creates an issue and classifies it as well as they can with either: bug, content, question or idea.

The issue is automatically labeled `Needs validation`. The `Needs validation` is added to avoid spam being exposed on the website and to make sure issues are addressed.

When removing `Needs validation` the issue should be assigned to a responsibility area or closed with a resolution label.
The current responsibility areas are:

* `portal`: issues that have to do with the presentation and bugs in behaviour.
* `api`: issues related to GBIF's apis (image cache, registry, occurrence, directory etc.)
* `content`: issues that are not about have we process the data, but about the data provided. Either by publishers or what we write in our CMS (Drupal).
* `question`: helpdesk questions

Resolution labels are:

* `done` - ideally reference to commit
* `duplicate` (refer to the duplicate)
* `invalid` (cannot reproduce, incomplete info etc)
* `wontfix`

So the procedure is:

* validate the issue.
* add appropriate labels
* (for portal and api) move to relevant repo and resolve as duplicate with a link to the new issue

This also means that for portal and api isues there is little point in starting a discussion on the issue before it has been moved.
## public labels
content issues that are labelled `public relevance` is public

## Content and questions
Since these issues reside in the repo they will probably need more labels. We probably want to seperate content provided by publishers from Drupal content issues.

## Notifications
You can change how and how often to be notified of activity here:
https://github.com/settings/notifications

See all notifications here:
https://github.com/notifications

and ask to be notified by using the eye in the top here:
https://github.com/gbif/portal-feedback

[see screenshot](https://gbif.box.com/s/wn685mdaxul687qo9d7x8gh4oiz4f78u)

## What will show on the site
Issues that are labeled `content` and do not have a `Needs validation` label will be visible on the site on the page the issue was created.
The fbitem[hash] refers to the url. 
This isn't an ideal solution, but it works for now and seems to be robust when using the Github search API.
