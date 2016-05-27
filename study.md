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
A view state is the current view that is displayed based on the state of the application. An example would be:
State: User failed log-in
View: Incorrect Password or username -- modal or screen
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essential parts of an Ember 2 application are Routes, Models, Templates (HTMLBars/Handlebars), and Components. There are also a host of services available for use at the developer's discretion.

Ember 2 differs from Ember 1.xx in that it has a default one-way data flow. It also employs a "just refresh it" philosophy. Apparently, there is also a lifecycle hook for components, but I don't know what this means.

Ember 1.13 is similar to Ember 2, but Ember 2 has removed the deprecated methods.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would build Ember when they are conciously choosing to rapidly develop a SPA that has finite states. Ember provides a framework, thus reducing the overhead to creating a new application.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember creates URLs which, according to Tom Dale, essesentially differentiate between a true web application and using the web as a content distribution network.
```
