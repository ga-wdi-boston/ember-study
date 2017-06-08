# Ember Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Before you get started, please read this exerpt from the first section of [a
blog post](http://pragmatic-backbone.com/routing-and-controllers) on
    Backbone's Router:

>"For the vast majority of cases, we want users to navigate through the app, and for the user to be able to go back to the screen they were using the browser history (back/forward buttons). These screens are in reality states of the app: *new book form visible*, *viewing a list of books I own*, *browsing a book*, and so on, are examples of possible states that the UI is in.

>As to what screen changes warrant a state, it depends on how granular you want the user experience to be. For instance, you may decide to show the new book form in place, perhaps right above my list of books, and not have a dedicated URL (or a page) for creating new books. Or maybe there’s a large volume of information to be filled in it and you’d like to avoid cluttering the screen, so it makes more sense for that form to live in a screen of its own.

>The point is that while common sense (and known patterns) will provide great guidelines when it comes to deciding that, without taking UX into consideration, there are no absolutes. Backbone, like Ember or Angular, will give you a tool for creating screen states with URLs. Choosing what's appropriate is up to you and what you're building.

>Hence if and where you choose to have state in your app, you’ll need to use the router for constructing the UI. The low-level logic for doing all that won't live in the router itself of course. Instead, it'll fetch data using models/collections, and it’ll instance and render views to display the data. Put simply: it's with the router that you'll 'assemble' your application where state applies."

## Required Readings

-   The Overview and Sections 1-4 of the [Ember.js Wikipedia page](https://en.wikipedia.org/wiki/Ember.js)
-   The [Ember CLI User Guide](http://ember-cli.com/user-guide/) (Just the
[Getting Started](https://ember-cli.com/user-guide/#getting-started) section)
-   [Ember.js - Guide](https://guides.emberjs.com/v2.11.0/getting-started/) (Just the
[Getting Started](https://guides.emberjs.com/v2.11.0/getting-started/) section)
-   [Ember.js - Tutorial](https://guides.emberjs.com/v2.11.0/tutorial/ember-cli/) (Just
the [Creating Your App](https://guides.emberjs.com/v2.11.0/tutorial/ember-cli/) section)

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
