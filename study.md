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
I found https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/ to be a really helpful article in answering these questions.

A view state is what elements of your app are visible to the user at any given time. front-end frameworks make it easier to manage view states and even let you pick specific URLs which will hold view states without having to completely rerender the app.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
The essential parts are routes, models, components and templates.

In Ember 2 the auto-refreshing local server was added, ArrayController and ObjectController have been deprecated in favor of the generic Controller. Attribute and Class binding has been improved, and block params have been added for use in handlebar helpers.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember, much like Rails, sets you up with best practices already in place which makes it easy for you to navigate the code, even as someone looking at it for the first time. This can also help prevent common coding mistakes like pluralization, capitalization, and misspelling.

Ember also comes equipped with valuable tools like a powerful inspector and an auto-refreshing local server.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember uses the back end idea of having a router, but for the front end. It doesn't refresh the page, but it changes the url depending on what view state you are in and it also keeps the back and forward buttons functional for going back to a previous view state. Instead of more conventional javascript apps where hitting back would take you to the entire previous web page you were visiting.
```
