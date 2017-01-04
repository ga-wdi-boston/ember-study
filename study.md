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
A view state is the current state of the view at a given point in time. A front-end framework updates the view state based on user interaction.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Essential parts of an Ember 2 application:
1. Router - maps a URL to a route
2. Route Handler - loads a template and respective model
3. Template - loads components and accesses model data

The Ember 2 release contained a lot of "garbage collection".  They seemed to do a good job of releasing periodic updates to make it easier for developers to update their code in small areas at a time.  So in Ember 2 they cleaned up a lot of the old code that was no longer supported.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
It seems like Ember has a lot of defined best practices.  They have guides designed to help you get a new app setup and a lot of documentation surrounding naming conventions, etc.  They also have built in best practices that will warn you when you're not following them.  Some of it sounds a bit like Rails as well where it can save you from writing a lot of boilerplate code.

Also as mentioned previously, it sounds like they put a lot of thought into how to upgrade Ember without causing developers to completely re-write their apps to make use of the new version (unlike Angular).
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
By providing URLs for each of it's routes. Any time a new URL is set (via page load, back button, etc.), the router maps the current URL to a route handler.
```
