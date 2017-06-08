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
A view-state refers to what elements are being rendered on the client at
any given time. A front-end framework facilitates navigating between
view states via routes.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

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
