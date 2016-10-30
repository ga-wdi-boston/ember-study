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

A view state is a combination of what appears on the client side at any given time: both DOM elements and data. Front end frameworks help manage these states.

Resources: class notes/lecture


```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md

Core parts:

- Router (maps URL to route)
- Routes (load a template and a model/data)
- Model (store data on a server or in Local Storage)
- Template (displays data + desired DOM elements for a route)
  - templates in Ember use Handlebars 
- Components (template + behavior defined in a JS file)

Changes in Ember 2 (not all of these were released in Ember 2.0; some may still be in the works):

- Ember 2 removed old/deprecated features and code that had build up in Ember 1. 
- Ember Data became a stable part of Ember.
- Binding data with angle brackets instead of double curly braces. This is part of a "data down, actions up" approach that means templates don't by default update data (data binding is one-way, not two-way).
- Ember 2 uses the Glimmer rendering engine, which rerenders only the parts of a template that have changed. This makes things faster.

Resources: Ember docs, http://emberjs.com/blog/2015/05/10/run-up-to-two-oh.html, http://emberjs.com/blog/2015/08/13/ember-2-0-released.html

```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md

Using Ember lets you better organize your code and write a JavaScript app with client-side routing.

```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md

URLs are critical to the web—for sharing, for bookmarking, etc. JavaScript apps can exist entirely without URLs, and the single-page apps we've built in GA to date only use a single URL, meaning we can't share or link to any specific pieces of the app. Ember (and other front-end frameworks) let us use URLs, restoring this functionality. In particular, Ember uses nested routes to more clearly connect URLs to desired UI/view states.

Resources: Tom Dale talk

```
