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
I found https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/ to be a really helpful article in answering these questions.

A view state is what elements of your app are visible to the user at any given time. front-end frameworks make it easier to manage view states and even let you pick specific URLs which will hold view states without having to completely rerender the app.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

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
