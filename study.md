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
It contains specific properties in a controller, so each state can be maintained between two sessions. Each view state has its own route.

View state is related to front end frameworks through routes that determine what is visible for the user.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Ember 2 is simplier. First concept is the Ember object model that extend JavaScript objects to provide core framework functions. Other concepts are fundamental building blocks such as routing, model, services, and components.

Some of the deperecated features are:
- ArrayController and ObjectController (switched to generic Controller class);
- Binding classes to properties is simpler;
- Block params ({{#each people as |person| }} instead of {{#each person in people}})
- etc.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Because of its great features. Ember routes allows you to stop breaking the web. With Ember we get URL and back button by default with every route.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember stops breaking the web by providing routes that connect each view state. URLs are essential in order for app to work. Routes point to a different view state with button that leads to the previous state without breaking the web application flow.
```
