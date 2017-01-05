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
'View state' refers to the present condition of displayed data and UI elements for a given application.  Managing 'view state'
is one of the principal goals of front end frameworks.  Generally speaking, front-end frameworks like ember are designed to 
make it easy to keep the view state in sync with the state of data models.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Key Parts: Router, Route, Model, Component, Service

One of the most significant changes between ember 1 and ember 2 is the introduction of the Glimmer 2 rendering engine, which, as I understand it, employs a rendering strategy similar to React in that it relies on virtual-dom-diffing to minimize the extent to which the application "touches" the DOM on any given state change.  Perhaps because of this shift in rendering strategy, ember is moving towards a one-way data flow model.

Ember 2 also deprecates the {{controller}} helper and removes legacy handlebars helpers in favor of a helpers module on the main Ember object.

```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember offers a comprehensive, opinionated, fully featured solution for front-end application management.  Moreover, it provides a helpful cli to ensure 
adherence to best practices with respect to file structure, semantic naming, etc.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember emphasizes the importance of URLs in complex javascript applications and especially SPAs.  Many front end frameworks treat URLs as an afterthought.
Once the user navigated to the root URL for the application, the URL became inert, not reflecting the state of the data shown on the page.  Ember, conversely, uses the URL to reflect the state of the application and, accordingly, can be used to reproduce a given state.
An ember application, therefore, creates semantically meaningful, shareable that, rather than simply reflecting the state of the application, actually move the application to that state.
```
