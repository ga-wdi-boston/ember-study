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
A view state comprises the layout of the page,
including which components are shown and which are hidden, or which
exist in the DOM at any given time. If you think about a DOM as a finite state
machines. Each of the states of the machine is a view state.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
An Ember 2 application has URLs which map through the router to view states.
The view states are really route handlers which interact with a model and data in a store
and then pass data to templates of mark-up. The templates often use reusable components.

Everything in Ember 2 was added incrementally to Ember 1 before Ember 2 was released.
Ember 2 is just about removing old stuff.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
The two way data binding makes it so you have really good seperation of concerns
across different features so you may want to use Ember has your application scales
so you don't end up with insane jQuery situations. The code will be modular
and very reusable since components are fairly abstract.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
One advantage of using a web application is that you can use URLs which
allow for things like forking your state, sharing, collaboration, and bookmarking.
Ember uses URLs to track state so it doesn't ignore those advantages of web apps.
Ignoring URLs is how people break the web. Also - it is nice that it has an MVC on the client
side because it minimizes calls to the API which makes it break the web less.
```
