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
View state is what is rendered on the client site at any given time. Front end
frameworks help manage the state of the view to the user.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
1. Routes - each route has its own URL
2. Models - contains data associated with the current state of the app.
3. Templates - used to build the app's HTML.
4. Components - custom HTMl tag, which is defined using templates.
5. Services

The biggest difference between ember 1 and 2 lie in the view layer.
Unidirectional flow of data(data down, action up, or DDAU) - Data flows one way
and there are no two-way bindings.
Standard lifecycle hooks for components.
Improved re-rendering performance, or Glimmer
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember works well with large application ecosystems.
It has a full fledged templating mechanism.
Client-side rendering and structure to scalable web applications beyond the
view layer.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Each route has its own URL.
```
