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
A view state is essentially a way to integrate highly flexible code into your program
in order to hide or show certain parts of a site without actually making them
entirely different files. It enhances ease of navigation and clarity of code.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Ember is easily backwards compatible, which is great moving forward into
Ember 2. An Ember 2 application has models, routes, templates that work like
handlebars, components, and services. Some of the main differences between
Ember 2 and Ember 1 are that Ember 2 adds hooks, is focused on stability, one
way data flow, and a new rendering engine called Glimmer.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember is a very comprehansive framework for creating SPA's, meaning the website
itself relies on viewstates rather than hardcoded pages for navigation. Ember is
flexible and has lots of other advantages over similar frameworks, depending on
its specific intended use. In general though, Ember is good for developing an SPA that
would benefit from view state incorporation.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember's focus on stability means that updates are easy to incorportate, making
for a more streamlined usage of the framework that requires minimal change on
sites that use older versions while providing adequate support for the newer versions.
Ember releases changes slowly over time so that they can be integrated in a more stable
secure manner.
```
