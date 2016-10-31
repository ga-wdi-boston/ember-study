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
a view state describes which elements are rendered and when.  A view state does not necessarily concern itself with how it transitions between other states.
It often reflects a model or multiple models as they change.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Components, routers, services, and models.  Also, the Ember object model which contains some/all of the aforementioned parts.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember shines best in complex, large-scale applications which have heavily interacting pieces and places where components can be reused significantly.
There is a lot of overhead to get it set up, but it makes large applications easy to manage and maintain over time as well as extend functionality,
since it allows many key attributes of OOP to be implemented in JavaScript (before classes et cetera became a native part of JS).
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
This refers to Ember's routing, which allows you to keep track of your own state via URLs and transition to and from previous states easily.  
This has other implications in that it allows your website to be more shareable since you can easily send semantic URLs to collaborators, friends, and
other denizens of the internet.  Without such routing, you can lose information if you try to navigate away to a different page, and you cannot as easily
describe to someone else how you got to the place you did on a website.
```
