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
A view state is the current state of the model. It is what the user is
seeing when they are in their client. So if we are looking at a book site, and
looking at `/books`, our view-state will be all of the books. If we are looking
at `/books/:id` our view-state will be a *single* book.

Front-end frameworks represent how we as developers get the user to experience
the view-state. As opposed to hardcoding something like
```js
$('.some-div').text(data)
```
In some crazy for-loop, frameworks allow us to process and show data more
effeciently.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Routes - or whatever the user sees, much like how we went to `/books` in Ruby
when we were accessing our backend
Models - this is where the route leads to and what data the user will see
Templates - how the data is translated onto the DOM using HTMLBars
Components - which is a custom HTML Tag that can be manipulated via JavaScript
 Unsure of how this is different than any other tag
Services - objects that hold data

A big change with the resolver which appears to do something for you?
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
To build a CMS, or any of the apps we have made. Removes us from `.hide() .show()`
hell.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Less and more accurate URLs
Sustainable and fast SPAs
```
