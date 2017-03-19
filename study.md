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
My understanding of view state is that it is what is currently displayed on the page
at any given moment. When we add features or buttons in development, we would like to
see if they are displayed where we intended them to and work as we want. Every time we
make a request to a server, the view state of our current page will likely change.
In regard to front-end frameworks, they affect the architecture of how things are rendered,
Controllers are dependent on the view in an MVC archtiecture. The clients controller code has many responsibilities.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
1. The routes, which control what is visible to the user in the URL.
2. Models, which are determined by the routes. They contain the data associated with the current state of the application.
3. Templates build an applications' HTML with HTMLBars, which I will learn more about.
4. Components - custom HTML tags, whose behavior is implemented with Javascript and HTMLBars define their appearance. Components "own" their data. They can be nested and communicate with their parents components.
5. Services - single objects to hold long-lived data.


```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Best practices are built into the Ember framework, so it is easy to reach out to the community that uses Ember, if any changes have been made that they should be awae of.
My understanding is that Ember is also relatively easy to learn compared to other frameworks, so it allows for easier training and larger code bases for teams to work on.
Ember already has the lastest ES6 and ES7 features built in, so there is no need for configuration.
https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
My understanding is that there are a variety of different web standards that sometimes conflict with each other and Ember attempts to solve this issue, by adapting and fitting those standards into its framework and by being involved in the committees that set these standards, so the risk of conflict is mitigated.
```
