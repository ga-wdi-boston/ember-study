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
A view state is just that: a state of viewing. The landing page is a view state,
the log-in screen is a view state, and most other "pages" are view states. Front-end
frameworks care about view states because they need to know what needs to be
displayed/hidden when the user performs certain actions.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Routes, models, templates, components, and services. These concepts are very
similar to the traditional MVC set-up that we've seen on the back end applied to
the front end (with some changes). Ember 2 added one way data flow, "just refresh
it" when something changes, and standard lifecycle hooks for components.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Ember has a lot of built-in best practices, which makes it very easy to build
great, stable apps. In addition to the usefulness of URLs and routing, Ember
values stability without stagnation (continues to develop new features without
leaving existing users behind), convention over configuration (fast set-up that
rarely has to be manually changed), and plug in architecture (other add-ons can
be easily implemented if desired).
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember makes use of URLs, which allows users to convey any state very easily. A
lot of apps make use of hide/show without updating the URL. This means that a
user could see any number of view states that correspond to "www.example.com".
However, with URLs, it's much easier to show specific "pages" such as
"www.example.com/posts/2". This can still be part of a single-page-app while
also gaining the benefits of specific routes.
```
