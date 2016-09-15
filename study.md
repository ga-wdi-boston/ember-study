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
The view state is the current URL route that is being viewed by the user.  Front end
frameworks keep track of what state the user is in and map via additional
routing the states that the user is selecting. The multiple URLs are able to be
viewed from one outputted screen.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Ember 2 uses Routers to display URLs to users.  The Models store the data and display it to the user as requested by the router.  Templates called HTMLBars are used in a Handlebars style format to render DOM elements on the page.  Componenets are the custom individual HTML tags that are created by HTMLBars and they store data attributes and can communicate with their parent elements.  Services just hold a single object that stores minimal details on a longer-lived data.

Ember 2 will update the page automatically after a developer saves their work while
editing.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember appears to be a faster way of rendering data and storing it on a page while minimizing communication with a back end.  This allows for faster responses to user requests for data, which is reflective of the current trend to push for client heavy processing.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember stops "breaking the web" by allowing people to use MVC frameworks in their SPAs instead of rendering just a single URL page.  With a front end framework, a person can share the correct locations and fork pages to other people because the complete "view state" can be procurred.
```
