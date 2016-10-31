# Ember Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   The Overview and Sections 1-3 of the Wikipedia page on [Finite-State Machines](https://en.wikipedia.org/wiki/Finite-state_machine)
    (just skim - don't get caught up on the details)
-   The first section of [this blog post](http://pragmatic-backbone.com/routing-and-controllers) on
    Backbone's Router.
-   The Overview and Sections 1-4 of the [Ember.js Wikipedia page](https://en.wikipedia.org/wiki/Ember.js)
-   The [Ember CLI User Guide](http://ember-cli.com/user-guide/)
    ("Getting Started" -> "Deployments")
-   [Ember.js - Guides and Tutorials](https://guides.emberjs.com/v2.4.0/) (yes,
    read them all)

## Required Viewing

-   [CascadiaJS 2013 - Tom Dale - Stop Breaking the Web - YouTube](https://www.youtube.com/watch?v=BQ6at0addi4)

Additionally, we highly recommend completing the **entire** [Try
Ember](https://www.codeschool.com/courses/try-ember) course from CodeSchool.

## Responses

### View State and UI Routing

Explain, in your own words, what a "view state" is, and how it relates to
 front-end frameworks.

```md
The view state refers to information that is created or set by the user (whether it's certain tabs selected,
completed forms, sorting of data) that can be maintained and referred back to at a later time. In other words,
a user can close an application in any state that it is in, and then it can be reopened, either on the same
device at a later time or on a new device and the old information would still appear/exist. It relates to front end frameworks because the information is not being stored in the back end - it is being stored by the use of
routing in the front end.

sources: https://www.npmjs.com/package/ember-view-state
https://guides.emberjs.com/v2.4.0/controllers/
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Essential parts of Ember app:
1) Object model
2) Routing
3) Models
4) Services
5) Components

Changes between Ember 1 and Ember 2:
The goal of the Ember 2 release was to make it simpler and to remove unnecessary
items that previously existed (it is referred to as a "garbage collection release).
Views have been removed in the latest version and have been replaced with components.
Controllers have also begun to be eliminated. Using controllers requires an addon going
forward. ReduceComputed and ArrayComputed have been removed. Ember.Helper is used instead
of the legacy handlebars helpers.

sources: http://emberjs.com/blog/2015/08/13/ember-2-0-released.html
https://emberigniter.com/5-essential-ember-2.0-concepts/
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would likely use Ember in the case that they want to implement a fast and
smooth user interface with less code. In order to make transitions between "views"
go quickly and smoothly, it can require a lot of code to make the routing and other
functionality interact. Ember can do some of the more complicated, code-heavy tasks
for you instead.

source: class notes
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember uses a concept called "stability without stagnation". Ember has used small,
incremental upgrades and released them over time, which has allowed them to
make changes without sacrificing compatibility with browsers or slowing things
down on the internet. 
```
