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
View states are the different 'views' of what you have on your screen, when your screen changes, and you're on the SPA, the view state has changed. Frameworks like Ember.js help to manage what view states you have with the routes & Url's  that you have in each view state.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
For Ember applications:
- Routes
- Services
- Models
- Templates
- Components

Some big changes between Ember and Ember 2:
- Component properties were immutable by default, so the data flow was one-way as a default. Standard life-cycle hooks, which would help when a component's attribute changes.(<!-- NOTE ask about lifecycle methods.-->)

```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would use ember if they enjoyed front-end work. Ember would help with facilitating the back button feature, and Ember has an object system that you can work on, instead of prototype based programming. Ember helps to develop scalable SPA's.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember 'stops breaking the web' because its router helped any SPA to be able to have one Url and add back button functionality. In this article: https://www.codeschool.com/blog/2015/10/26/7-reasons-to-use-ember-js/ I understood that Ember's API is very easy to use.```
