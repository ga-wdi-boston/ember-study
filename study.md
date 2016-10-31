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
The view state is essentially the current render of the app that the user sees. Front-end
frameworks are used to handle the state changes based on interactivity within the app, and manages
what gets rendered in a specific view state.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essential parts of an Ember 2 app are:
- Routes (an object that corresponds with a URL to control what the user sees)
- Models (every route is associated with a model, which contains the data associated with the current state of the app)
- Templates (these are used to build the app's HTML and written in HTMLBars, a variation of Handlebars)
- Components (this is a custom HTML tag and relies on JS in order to be implemented. Components 'own' their data)
- Services (these hold long-lived data, like user sessions)

The major changes from Ember 1 to Ember 2 are:
- Intro of Glimmer, a rendering machine, that has improved re-rendering performance.
(aka 'just refresh it' when something changes).
- One way data flow by default (data down, actions up)
- Standard lifecycle hooks for components (hooks allow you to run code at specific times in a component's life)
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember would be a good choice for someone looking to build projects faster, no matter the size.
Ember utilizes 'convention over configuration' which allows you to get started right away, without
having to manually change or build a lot of stuff.
It has tons of addons that can be implemented for custom features.
It has built-in best practices that are maintained by the core Ember team, which follows
the philosophy of Stability Without Stagnation (aka the framework will continue to evolve, but
will be careful not to move too quickly and leave current users behind).

Source: https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember has a built-in router feature, so URLs come into play when building your SPA in Ember.
This 'stops breaking the internet' because as JS-based SPA apps became more and more
popular, developers didn't use routes for these SPAs so sharing a specific view
state with a uniqure URL wasn't possible. Additionally, Ember allows your app to utilize
the back button with History API.
```
