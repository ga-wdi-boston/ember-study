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
A view state is what appears on the screen (what is rendered in the browswer)
at a given time when a page is loaded. A view state is comprised of both DOM
elements and data.

Front-end frameworks manage different view states by organizing the relationships
between them, and (for example) hiding or showing content based on events that a
user initiates, like clicking a button, filling out a form, or scrolling.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Essential Parts of an Ember 2 application are:
 **Routes** - each of an app's view states has a specific URL controlled by
 ember's routes.
 **Models** - Like a back-end frame-work, each route is associated with its own
 model, and in Ember the model contains data for each view state.
 **Templates** - Templates are used to build the view-state's HTML and Ember uses
 HTMLbars, a variation of handlebars, another templating engine.
 **Components** - A custom HTML tag that 'owns' its own data.
 **Services** -  Hold long-lived data, such as user-sessions.

 The major changes from Ember 1 to Ember 2 are:
 The biggest changes were made in the view layer, and included:
  - default one-way data flow
  - introduction of Glimmer, a rendering machine, that improves re-rending
  performance (ie, "just refresh it" when something changes).
  - standard lifecycle hooks for components (these execute whenver a component's attributes change).
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember is a good choice as a front-end framework for writing an application with code that is DRY (don't repeat yourself) because it allows one to fairly easily write an SPA with very little code repetition. Ember is also
a good technology for providing stability while continuing to improve upon and develop new features (avoiding stagnation). Lastly, Ember provides lots of tools for working with frequently changing data.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
URLs are crucial to the funcitonality of the Internet, by making things easily sharable. By utilizing URLs, which even the least technically-savvy end-users are familiar with, any view-state can be easily shared across browsers (and devices) with a simple copy-and-paste. Like other front-end frameworks, Ember allows us to retain the functionality of a particular view state by linking it with a specific URL, thus allowing us to share those view states with other users via the URLs, unlike the SPAs we've built so far in WDI.
```
