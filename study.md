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
A view state comprises which components are shown and which are hidden, or which
exist in the DOM at any given time. If you think about a DOM as a finite state
machines. Each of the states of the machine is a view state.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
<!-- your answer here -->
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
The two way data binding makes it so you have really good seperation of concerns
across different features so you may want to use Ember has your application scales
so you don't end up with insane jQuery situations. The code will be modular
and very reusable since components are fairly abstract.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
I think the point of using a web application is that you can use URLs which
allow for things like forking your state, sharing, collaboration, and bookmarking.
Ember uses URLs to track state so it doesn't ignore those advantages of web apps.
Ignoring URLs is how people break the web. Also - it is nice that it has an MVC on the client
side because it minimizes calls to the API which makes it break the web less.
```
