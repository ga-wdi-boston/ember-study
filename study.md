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
A view state is the content that is visible to the user at any given time over the course of their interaction with a web app.  Front-end frameworks such as Ember manipulate this state with routers and url's to update the DOM and create different browser renderings for the user.

(source: https://guides.emberjs.com/v1.10.0/understanding-ember/the-view-layer/)
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Parts of an Ember 2 application-
Routes- url's that update the view state
Models- data associated with the view state
Templates- builds HTML using HTMLBars (variant of handlebars)
Components- don't fully understand these yet
Services- objects that contain long-term data

Changes between Ember 1 and 2-
Default one-way data flow
'Just refresh it' for a change
Introduction of Glimmer to improve rendering performance

(source: https://en.wikipedia.org/wiki/Ember.js)
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
It seems like one of the main benefits of Ember is ease of use and speed of setup which allow for developers to be more productive overall.  Also chipotle uses it so it must be good.

(source: https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/)
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
JavaScript web apps go against the grain of the early days on the web in the sense that entire applications are consolidated under one url.  Ember reverses that trend by adding url's with every route created, giving the app greater functionality in that it can still be a SPA but have distinct url's that can be bookmarked and shared.

(soure:
Jason's router session and https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/)
```
