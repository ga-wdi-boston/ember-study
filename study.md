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
A view state is a specific view of the app (the current dom and the data that is being requested/rendered). Front end frameworks are used to manage the many different view states of an app.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Ember 2 has:
Routes: Each of an apps view states has a specific URL, these URL are controlled by ember's routes.

Models: Like an API model, ember models contain data for each specific view state.

Services: These keep track of data to be saved.

Components: An isolated view for specific data.

Re-rendering improved in Ember 2 and one way data flow was added (data is sent to the client and actions are sent to the server).
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember gives developers the resources to create an app that has distinct view states that correspond with distinct URLs. The wrokflow is structured and follows practices seen in rails and writing traditional javascript.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember breaks the practice of havin one static URL for the entire application. When using ember we can assign unique URLs to any view of the app we want, and access them accordingly (moving 'forwards' or 'backwards').
```
