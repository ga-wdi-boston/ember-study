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
State is persisted data. Routers in front-end frameworks use the changing of state
to trigger other events.

```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essential parts of Ember 2 include the "one way flow of data", automatic refreshing
of data, "standard lifecycle hooks for components" and the glimmer render
machine - similar to the virtual DOM used by React.

The main difference between Ember 1 versions and 2.0 is the removal of depreciated
changes.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would use ember if they want record state in their web apps to make
changing the view state as a result of an event easier and they want to have different
urls for each view state.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember's stops breaking the web because of its ability to record view state in a url
and allow users to better collaborate, fork web apps, and bookmark views which
can't be achieved with desktop apps.
```
