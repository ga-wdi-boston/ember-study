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
View state is what the common user thinks as a different page.
It's what the user is looking at and interacting with and what data is
currently being served and if the user navigates to a different view state, it
sends the route to that view state in the url and makes that request without
actually refreshing the browser.

The refresh of the browser is what distinguishes it from a page.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Ember 2.0 collected the garbage out of Ember 1.

-alot of deprecation
-compatibitilty with ember inspector
-views removed from Ember components
-controllers eliminated
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
It cleans up JQuery SO much.

It eliminates the need to manually hide everything and show the "page" you want
or it elimnates the need for manually creating hrefs and routes for
a single page applicaton. Client side routes also allow History so users can
press the back button and see the last view state they were at.

Ember also eliminates the overdoing of get requests by storing data on the client.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember gives client side routing to different templates rather than having to
on initial load serve ALL the HTML to the browser then from there just show and hide

```
