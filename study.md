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
A "view state" is where you have navigated to within a website (from one location
to another location within the site). In a front-end frameworks, this relates
to the view that is being rendered based upon an event.  For example, someone
can navigate from the homepage to About Me, and that will change
the view state of the page to render the About Me portion of code and hide the
homepage.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The essential parts of an Ember 2 application are the changes to the view
layer, which includes one way data flow, automatic refreshing of the page
when a change is made, and lifecycle hooks for components.  One major change
from Ember 1 is that views can no longer be accessed from the global scope.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember would be a great framework to use because it's highly opinionated, so
best-practices are always upheld.  It also has built-in testing, so you know
that your app is responding properly to user input.  It also does a lot for the
user and navigation within an app because users can go back and forth
between view states without exiting the app if they hit the back button.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
I don't entirely know what "stop breaking the web" means, but I think it means
that apps that use new technologies can have difficulty being rendered properly
in older browsers.  With Ember, you can use Babel.js to render new JS
idioms in older browsers.  For example, when using plain old JS, the fat arrow
may not work properly in IE7 (gross), but with Ember/Babel, it will.
```
