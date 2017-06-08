# Ember Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Before you get started, please read this exerpt from the first section of [a
blog post](http://pragmatic-backbone.com/routing-and-controllers) on
    Backbone's Router:

>"For the vast majority of cases, we want users to navigate through the app, and for the user to be able to go back to the screen they were using the browser history (back/forward buttons). These screens are in reality states of the app: *new book form visible*, *viewing a list of books I own*, *browsing a book*, and so on, are examples of possible states that the UI is in.

>As to what screen changes warrant a state, it depends on how granular you want the user experience to be. For instance, you may decide to show the new book form in place, perhaps right above my list of books, and not have a dedicated URL (or a page) for creating new books. Or maybe there’s a large volume of information to be filled in it and you’d like to avoid cluttering the screen, so it makes more sense for that form to live in a screen of its own.

>The point is that while common sense (and known patterns) will provide great guidelines when it comes to deciding that, without taking UX into consideration, there are no absolutes. Backbone, like Ember or Angular, will give you a tool for creating screen states with URLs. Choosing what's appropriate is up to you and what you're building.

>Hence if and where you choose to have state in your app, you’ll need to use the router for constructing the UI. The low-level logic for doing all that won't live in the router itself of course. Instead, it'll fetch data using models/collections, and it’ll instance and render views to display the data. Put simply: it's with the router that you'll 'assemble' your application where state applies."

## Required Readings

-   The Overview and Sections 1-4 of the [Ember.js Wikipedia page](https://en.wikipedia.org/wiki/Ember.js)
-   The [Ember CLI User Guide](http://ember-cli.com/user-guide/) (Just the
[Getting Started](https://ember-cli.com/user-guide/#getting-started) section)
-   [Ember.js - Guide](https://guides.emberjs.com/v2.11.0/getting-started/) (Just the
[Getting Started](https://guides.emberjs.com/v2.11.0/getting-started/) section)
-   [Ember.js - Tutorial](https://guides.emberjs.com/v2.11.0/tutorial/ember-cli/) (Just
the [Creating Your App](https://guides.emberjs.com/v2.11.0/tutorial/ember-cli/) section)

## Required Viewing

-   [CascadiaJS 2013 - Tom Dale - Stop Breaking the Web - YouTube](https://www.youtube.com/watch?v=BQ6at0addi4)

Additionally, we highly recommend completing the **entire** [Try
Ember](https://www.codeschool.com/courses/try-ember) course from CodeSchool.

## Responses

### View State and UI Routing

Explain, in your own words, what a "view state" is, and how it relates to
 front-end frameworks.

```md
If a state describes the current status of the system, then a view state describes
the status of the client at a particular instant in time. A view state has all the stored
information at that given time in the UI. So as a user is navigating the application,
going through different "screens" or "pages" he or she will be in different view states.
But of course, it is up to the developer's discretion to decide which parts of the
app will have its own view state.   

A view state is also waiting on certain inputs that will trigger a transition to
a different state in which case front end frameworks would have a role in executing
the transition and rendering information or data that has been appropriated to such state.
This is precisely where front end routing plays an important role in assembling and
putting together the view states.
```

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
Essential parts include:
 - Routes
 - Models
 - Templates
 - Components
 - Services

The first thing that happens when the user visits a URL is that the Ember router maps
the URL to a route handler. The route handler then typically does two things:
  - It renders a template.
  - It loads a model that is then available to the template.

Ember uses templates to organize the layout of HTML in an app.

Models represent persistent state; in other words, information can continue to exist,
typically in the web server or the browser's local storage.

While templates describe how a user interface looks, components control how the
user interface behaves. Components consist of two parts: a template written in
Handlebars, and a source file written in JavaScript that defines the component's behavior.

The addition of the Glimmer rendering engine was a major change, and that in itself
brought in a whole load of new features such as one-way values by default for template
bindings, fast re-render and new lifecycle hooks.
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
Like Ruby on Rails, Ember preaches the idea of "convention over configuration". This
makes it easier to get started on a project right away without worrying about so many
choices since the choices made by the framework lines up with the collective best
practices of the software community.

Out of the box Ember has a number of different productivity-enhancers such as Babel.js,
which is able to handle the most updated version of JavaScript and transcribe to
browsers that are lagging behind, and Broccoli.js – an extremely efficient build system
that is capable of compiling code quite quickly. Testing is also built in the Ember
toolbox.

```

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
Ember actually makes use of URLs and routing, which removes the idea of using the
web simply as a distribution mechanism for a developer's native application, and
promotes the use of a smarter client that encourages sharing and mirrors the MVC
architecture to give a developer greater control in their front-end development process. 

```
