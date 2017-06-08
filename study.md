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
A view state is what is getting rendered in the UI at any given time during a
user's experience with an application. It is a *view* that is dependent on the
*state* of the app. When something causes a change in app state, such as a
button click or new content being pushed from the server, a well-designed app
will respond to the change by transitioning into a different view state.

Front-end frameworks help developers achieve this component of good app design
by doing much of the work required to listen for changes in app state and
trigger the appropriate state-dependent changes in the UI.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
An Ember 2 application has five essential parts:
-  **routing**, which links app state to the UI via URLs and their associated routes
-  **models** - each route has a model. Models are where state lives.
-  **templates** are how the page's HTML gets built. Ember uses a templating language called HTMLBars
-  **services** - objects that store data that needs to persist across routes (like tokens)
-  **components** - HTML tags with custom behavior (via JavaScript) and appearance (via templates)

According the Ember 2.0 release notes, the primary goal of 2.0 was to streamline
Ember and remove features that had become redundant or unecessary. Most of the
substantive changes since Ember 1.0 were accomplished in point releases before
2.0. Improving support for web components was a big part of the run-up to 2.0.
So was the one-way data-binding principle known as "data down, actions up". They
have also worked to improve re-rendering performance, possibly in direct
response to React's success with this.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
A developer would use Ember to give their client-side application a lot of
structure right out of the box, and to impose a lot of front-end best practices,
standards, and conventions on their application with minimal effort. It allows a
front-end developer to build a state-dependent UI in a proven, standardized way.
Many front-end frameworks offer these things; Ember is also a great choice
because of its ongoing commitment to backward compatibility while staying
up-to-date with new development technology, such as web components and promises.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember stops breaking the web by restoring a nuanced sense of navigation to URLs.
The first generation of single-page applications (SPAs) inhibited users'
ability to share, collaborate on, and bookmark specific content by hiding a lot
of different view states within a single URL. Ember, and other front-end
frameworks that incorporate routing, supports the division of an SPA into
semantically named view states that correspond to different URLs. This divides
the content of an SPA into discretely named pieces that users can easily
navigate, share and save.
```
