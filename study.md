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
Translate primitive browser events (e.g. click) to events with semantic
meaning to the application. These semantic events are first sent up to the
controller, or if no method is defined there, your application's router,
which is responsible for reacting to the event based on the current state
of the application.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essentials part of Ember 2 applications are the Object Model, Routing,
Models, Services, and Components.
The goal of Ember 2 wasn't to add new features but reduce accumulated
cruft aka built up garbage.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Given that it's an opinionated framework, saves time in making
architectural decisions for you. Additionally, helps with organizing
code into moduals, setting up build tools, creating mock servers for testing,
and sharing common functionality across the community. In a nutshell,
saves time and let's you write cleaner, simpler code.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Originally, the URL allowed the linking of specific pieces of content. However,
this was broken by JavaScript applications by using a single URL which cause
problems with the back button for example. Ember's Router let's you "stop breaking
the web" as you get URLs with every route you create.
```
