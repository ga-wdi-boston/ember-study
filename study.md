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
It is info set by the user, the changes -and how she/he plays around with the
front end. It related to front-end frameworks because such variations do not get
stored in the back-end but in the front-end routing.
https://www.npmjs.com/package/ember-view-state
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Ember 2 is called a garbage collection release, meaning that it removed
unuseful items off Ember 1. Views and controllers are now replaced by components, which are isolated views for specific data. Routing also is a part of ember 2 and URLs are controlled by Ember's routing. Models also have data for a specific view state.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
To be able to have many view state with different URLs. Also, ember might
remind a developer of rails and writing some js. Plus, routing is made easier.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember stopped the usual practice of having one URL for the entire site, and
introduced distinct URLs for different view states.
```
