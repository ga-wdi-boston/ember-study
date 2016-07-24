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
A view state is a certain rendering of the application that looks different from when the app is in a different state. They relate to front-end frameworks because front-end frameworks provide a way to dynamically set different view-states ahead of time at different urls and trigger changes between them while changing the url but also not refreshing the page.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Essential parts of an Ember 2 application are: templates, which are the html that is displayed when a user visits a certain url, a route handler to get models which those templates are attached to, a router, to connect a url to one of those routes, components (which are more general templates that can be used repeatedly in different more specific templates),

So...components make up a template. A template is fetched by a route handler, and the router directs the route handler. (https://guides.emberjs.com/v2.4.0/)

Changes that have happened between Ember 1 and Ember 2 are that data now by default only flows down (one way) instead of two, and standard lifecycle hooks for components were added. It also introduced the use of the Glimmer rendering engine. (https://en.wikipedia.org/wiki/Ember.js)
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would use Ember in order to be able to dynamically change states without refreshing the page via a front end router that allows them to still use different urls for different states.

It also is good for keeping code dry and avoiding "jquery spaghetti" (I know we're supposed to put things in our own words, but I just loved that phrase too much because I TOTALLY feel it describes the mess of repetitive junk I wrote to change states in my initial projects).
(https://www.youtube.com/watch?v=BQ6at0addi4)
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember stops breaking the web because it uses different urls to access different view states instead of only one url with shifting view states all of the time.
(https://www.youtube.com/watch?v=BQ6at0addi4)
```
