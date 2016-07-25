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
A view state is one of the possible ui states that a user might want to access
within a web app. Within the MVC or MVVM models, view render data from a model into html or html template and then allow the browser to draw that data into the
window. Users can then interact with rendered DOM elements, and user actions are translated into changes in the view state by the controller of a front-end framework.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Routers, models, templates, components and services. In Ember 2, components and services replace the functionality previously provided by views and controllers.

Ember 2 made some changes in the way that the view works. By default data only flows down from the model, and the users only determine changes in the view by actions. Ember 2 also uses Glimmer to improve the speed at which a browser window renders in a way similar to React. Backbone seeks to speed up rendering by loading HTML and CSS while waiting for the rest of the JavaScript to resolve.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember allows easy rendering of html elements that correspond to back-end entities, and has a natural congruity with the structure of urls.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
In Yahuda Katz's talk, he made the comparison or urls to telephone numbers; their existence may be a historical accident, but their incredible utility ensured that they were used much longer than might be necessary for the technology. His main point is that we should be designing the web, specifically by using the functionality of urls, to take advantage of the structures that users gravitate towards, instead of imposing a top down structure that ignores their intuitive wishes.
```
