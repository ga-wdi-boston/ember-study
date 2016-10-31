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
Modern day websites are SPA's(single page applications) which utilizes "view state"
to guide a user through the client app/site. A SPA webpage has many states which can
be changed depending on user interaction. Front-end frameworks help aid in the
development of a rich and dynamic user experience.

```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Routes - state represented in URL which corresponds to a route object that controls user view
Models - every state has a model which contains all the data associated with the state
Templates - used to build HTML with HTMLBars which is a version for handlebars
Compenents - a custom HTML tag that is used to HTMLBars
Services - objects that hold user session data

Ember 2 got rid of old APIs and added glimmer
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Like the Rails framework, Ember provides a quick and easy way to create a front-end
web application with minimal coding and provides a host of build in tools to aid
the development process.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember allows specific URLs which corresponds different view states in a web app
instead of a static url.
```
