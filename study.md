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
A view state is, in essence, a certain 'screen' of our app that the user
sees on the client side. It's a combination of DOM elements and data.
Front-end frameworks help manage these different view states in the app.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md

Core Parts of an Ember 2 application are:
- **Routes** - each state of the app has a URL, each URL has a corresponding route that controls what is visible to the user
- **Models** - Every route has an associated model, which contains the current state's data
- **Templates** - Where we build the app's HTML, using HTMLBars
- **Components** - A custom HTML tag that 'owns' its own data and can communicate with parent components through actions / events
- **Services** - Objects that hold long-lived data like user-sessions

Major differences between Ember 1 and Ember 2 include:

- The addition of the Glimmer redinering engine that vastly improves re-render performance
- One way data flow (data down, actions up)
- Standard lifecycle hooks, which execute whenever a component's attributes change
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember provides the framework to 'quickly' (relatively) and easily write a fully functional front-end web app with minimal code repetition and it follows a similar structure to JavaScript or Rails servers, making it easier to keep our code organized. It also provides a lot of built in tools for working with constantly changing data.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
The web has, traditionally, relied on URLs as a way to define and identify the path of the site we are on. Thus far in GA, all of our SPAs have only had one URL that remains static no matter which viewstate we are in. Ember, however, allows us to assign specific URLs to every view state in our app, allowing for greater specificity when linking and retaining the functionality of the URL path.
```
