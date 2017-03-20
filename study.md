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
A view state is a concept in single page applications where each part of the
user experience and webpage that a user sees, while seemingly a different page,
is in reality just uniquely rendered html. It relates to front-end frameworks
because the display of webpages and routing of URLs is done much more on the
client side using these front-end frameworks instead of on the back-end.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
The essential parts of an Ember 2 application include the router which define
routes that link to templates & views which are handlebars files that contain HTML
that are loaded onto the browser. Next is the model which contains the underlying
data the app renders to the user. The final essential part of an ember app is
the component which are custom HTML tags where templates are rendered.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
It acts to guide the developer through the web building process in addition to
accommodating contemporary and forward thinking javascript. In addition, it utilizes
live refreshing so that when code changes are made during development manual page
refreshes are no longer necessary. It in essence acts in the developer's best
interests to incorporate best practices into the development process.

```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember stops breaking the web by creating an easy to use API that utilizes URLs
via routers that also allows the user to use the back button. I was unsure after
watching the video about this question but it definitely has something to do with
how Ember uses the router to render HTML to the user. Hoping this question
becomes clearer as I explore ember this week in class.
```
