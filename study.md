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
The view state is what the user is currently viewing.  It's kind of crazy, but I believe that somehow, with ember we're going to be altering what our HTML is showing us without going to a new page or using jQuery to hide and show different elements.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Routes


Models


Templates

Components

Services


Some major changes include :

One way data flow by default. (Referred to as "data down, actions up".)
"Just refresh it" when something changes.
Standard lifecycle hooks for components.

introduction of Glimmer rendering engine

via Wikipedia article: https://en.wikipedia.org/wiki/Ember.js

<!-- your answer here -->
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
allows user to have a working back button to go back in the SPA.  As a common internet user, i love me my back button.

Additionally, it  :

-integrates well with large teams

https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/

```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Not sure, but it has something to do with creating new URL's dynamically in thew view state in ember verses going to new sub pages on the web. 

  ```
