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
View states are the "screens" that compromise an app. The different views
that we would like users to be able to return to via a URL. Front-end frameworks
allow us to manage these view states by profiding mechanisms to build this relationship
between what is being shown on the screen and the data being retrieved to be shown,
and make the process of showing that data repeatable via URL addresses.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essential parts of an Ember 2 application are routes, models, templates,
compenents and services.

In Ember 2 several changes were made to the view layer including one way data
flow by default, "just refresh it" when something changes, and standard lifecycle
hooks for components.

Ember 2 also introduced the Glimmer rendering engine which improves re-render
performance by only updating parts of the DOM that have been updated, using a
virtual tree.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would use Ember if they want to create a single-page application
with many views, which can be accessed by URLs. This allows the advantages
of SPAs while also allowing links to be shared to specific views within the app.
This would be key if, for instance, you were creating an image-upload site or a
classifieds listing or any number of other apps.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember "stops breaking the web" by allowing developers to manage views, and tie
them into URLs to be easily bookmarkable, shareable, forkable and enable collaboration.
```
