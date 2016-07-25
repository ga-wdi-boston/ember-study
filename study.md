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
View state represents how the app looks to the end user at any given moment.
Front end frameworks track the view state so that it can react appropriately when the user interacts with the application.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The key components of an ember 2 app are routes, models, templates, components,
and services.  In ember 1, the framework used views and controllers instead of
the components and services implemented in ember 2.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
A developer would use ember as a more complete way to implement an MVC client as
opposed to some other frameworks that focus on the view state, ember seems to
start from the route as a base and build the view up from there via the model
and the controller.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember uses the data provided in the URL to be able to determine the state of the
app at any given time, allowing the app to be easily shared/replicated via the URL.
```
