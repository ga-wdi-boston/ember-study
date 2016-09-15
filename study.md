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

 Think of views like what user will see or intereact with. Having a landing page, a register page, and a showSomething page. Each of those pages with ember will have a separate view or html url. Ember and frameworks are different than what we have been doing. The view states and the routes are separated(into categories in a way), so that there is a 1:1 ratio with the route and the model, with that pairing there is also a corresponding url given.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?
What changes have happened between Ember 1 and Ember 2?

```md
The big changes between Ember version one and two were changes in the view layer(in terms of the MVC or MVVC in the case of ember). There is one way data flow without having to specify it.
There was the creation of the Gimmer rendering engine. It uses the DOM to do so. It seems to be similar to react, so glimmer seems to be similar to the virtual DOM in react.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Someone would use ember if they want to use something across html and javascript seemlessly. USing a framework like ember which has two way binding and it seems that ember even comes with its own code generator for creating models and the like for file directory maintanence. Learning about the ember inspector and fastboot, makes me really excited to learn ember and use these things in action. I understand that we probably won't use fastboot but the mere fact that it exists is exciting!
```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
It stops breaking the internet by creating a better way of how to manage the mvc. Ember enables this 'navigation' to be much more seemless. This way it makes working on multiple parts of the project smoother. The video brought up the concept several times of which model, which view, which controller. And that right there is how ember attempts to stop breaking. Ember also created two micro libraries which people using other frameworks can use to help with the issue other frameworks have of not having routers. Nested URLS will be really interesting to learn.
```
