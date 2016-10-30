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
A view state is, in essence, a certain 'screen' of our app that the user
sees on the client side. It's a combination of DOM elements and data.
Front-end frameworks help manage these different view states in the app.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

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
