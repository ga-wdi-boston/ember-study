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
I would appreciate some feedback on this, since I don't quite understand. But
with the inclusion of the finite state machine wikipedia article in this study,
it seems like a view state is something similar. That is, it's the representation
of the state that the system is currently in. Something can trigger a transition
to a new state, and it will no longer be in the state it was in previously.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
Essentials: routes, models, templates, components.
Changes: Ember 2 is basically Ember 1, but removes features that were marked as
deprecated since release 1.13. Ember 2 is essentially Ember 1.13+ without
deprecated features.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
The Ember development team claims to be forward thinking, integrating new web
standards into their product. From the talk in the study, it seems like it might
be easier for teams to work with Ember, since each component of a web page can
be broken up into an MVC and MVCs can be nested. It's free. It integrates the
concept of a router, bringing back application control through urls, unbreaking
the web.
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
I don't know, but I can try to digest and summarize some of Tom Dale's comments from
his CascadiaJS presentation. Ember stops breaking the web by relying on the use of
urls again, since the web is predicated on the use of urls for resource sharing
and mapping to documents/things. It's completely possible to make an application
that is run in the browser which handles all operations, internally (?), and does
not rely on urls to update the view or interact with models. This would mean that
the end user is not able to navigate through the application using the forward
or back buttons of a browser, nor could they navigate the application using the
address bar.
```
