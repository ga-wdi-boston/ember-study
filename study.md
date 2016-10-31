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
A view-state refers to what elements are being rendered on the client at
any given time. A front-end framework facilitates navigating between
view states via routes.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md

Essential parts of an Ember 2 application:
Routes: the state of the app as represented by a URL.
Models: Routes have associated models that contain data associated with current
state of app.
Templates: build app's HTML and are written with HTMLBars(variation of Handlebars)
Components: Custom HTML tags. Owns its data and can communicate with parent components via
actions or events.
Services: Singleton objects to hold long-live data (ex: user sessions)

Changes:
Ember 2 removes many unnecessary and depricated features.
Uses angle brackets ("<") instead of {{}}
One-way data flow by default(actions only sent to the server, data only sent to client)
"Just refresh it" when something changes
Lifecycle hooks: they let you run code at specific times during the component's "life"
Glimmer rendering engine added for improving re-render performance

```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Because it is a front-end framework that helps keep your code more organized. Its
organization reminds me a bit of Ruby on Rails, and I can easily see these
two frameworks going together (for front end and backend respectively) very well in a project.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
It facilitates routing, using urls to navigate between view states instead
of, for example, relying on jQuery to .hide() and .show(), which only
changes the view state superficially.
```
