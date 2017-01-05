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
A view state is responsible for responding to user events (e.g., clicks, drags, and scrolls), as well as updating the contents of the DOM when the data underlying the view changes. Views and templates work together to create the front-end user interface.

Ember's view hierarchy has the concept of child views, whereby Ember is responsible for re-rendering and inserting the child views, rather than the application code.

Source: https://guides.emberjs.com/v1.10.0/understanding-ember/the-view-layer/
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Essential parts of an Ember appliction include:
* Routes
* Models
* Templates
* Components
* Services

The biggest changes in Ember 2 occured in the view state.
* One-way data flow by default
* "Just refresh it" when something changes
* Standard lifecycle hooks for components
* Introduction of the Glimmer rendering engine
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
One good reason to use Ember is that it makes it easy to integrate with large teams since the codebase for every project will look virtually the same for every Ember app, thus decreasing knowledge overhead to quickly make meaningful changes.

Other reasons include the Router which allow us to have URLs and a working back button by default for our SPAs, as well as the tons of add-ons that are available such as Ember Data for persisting your state and liquid-fire for page animations.

Source: https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
'Breaking the web' refers to how web apps need to refer to URLs to to really qualify as web apps, otherwise you might as well we be building a native application.
```
