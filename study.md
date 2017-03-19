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
As far as I understand it, a view state refers to the actual content being displayed on the screen, particularly when displaying information received from the server. It realtes to front end frameworks because the entire intent of these frameworks is to facilitate transitions between various view states. In the cases of some frameworks, such as Ember, these view states are naturally mapped to URLs allowing users to share or easily recreate a certain state of the page.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
If I have understood correctly, the essential parts of an Ember 2 application are the Router, the Models, their respective Components, and Services which can serve a number of functions.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
The most obvious reason is the anser to why someone would use any front end framework: it is much faster to stand up an app, and removes the need to write repetitive, standard jQuery for DOM manipulation.

As to why someone might use Ember in particular, it handles mapping URLs to the MVC model very well, since it is built around that idea. It also has a number of strong opinions about web design, allowing it to implement those perhaps more effectively than the more flexible frameworks. Thus, if you agree with those opinions (or at least if they are applicable to the specific app) it might provide a more efficient solution to your problem.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
The web is being "broken" by a shift away from URLs, a side effect of the popularity of single page application. While this is perhaps not as much of a concern in 2017, at the time of the video being referenced perhaps it was. In essence, Ember "stops breaking the web" by leveraging the fact that URLs map well to the MVC pattern to provide a framework that is perhaps inseparable from the URL. Thus the strengths of the web that derive from URLs, primarily sharing, opening things in new tabs with a preserved state, and collaboration, are not only preserved but arguably enhanced.
```
