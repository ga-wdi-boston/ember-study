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
A view state determins whether or not certain information is currently viewable by the user. This makes it easier for an SPA to controll it's "pages" or "views" making an app with the advantages of both an SPA and a more traditional site.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essential components are routes, models, templates, components, and services. Ember 2 implementted one way data flow, data down and actions up, active refresh when something changes, and standard lifcycle hooks for components. A new render engine was also implemented for better re-rendering performance, presumably to accomodate for the active refresh.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember allows for fast paced development, better control over the content of a page, and a great deal of extensability. It helps devs to get up and running quickly, even when dealing with complex site features.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
By creating routed urls to allow bookmarking, collaboration, sharing, and forking inside an SPA.
```
