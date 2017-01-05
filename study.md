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
A view state is simply one set of content and styles that is visible to a user at a given time, along with information what actions will cause a shift to a different view state. Front-End frameworks like Ember are structured around this concept, using routers and URLs to switch between states.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
An Ember 2 applciation consists of:
- Routes, which handle tying URLs to view states;
- Models, which are associated with routes and hold application state data;
- Templates, which build the application's HTML using a handlebars variant;
- Components, which describe how a user interface behaves, and
- Services, which are objects that hold data such as user session info.

The features of Ember 2 have actually mostly already been released in Ember 1.x; the main difference is that in Ember 2 deprecated features have been removed.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
I'm excited about Ember. It seems like a great way to easily set up a robust and semantically structured front-end web app without having to write all the low-level code yourself.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
The web runs on URLs--so if you build an app that doesn't take advantage of that, you aren't really using the web like it's meant to be used. Ember leverages URLs to make apps that feel like native apps but are really web apps.
```
