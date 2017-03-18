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
<!-- View state is current representation of the values of data that the user sees when loading a page while the framework that data is loaded into stays the same. Front end frameworks allow for the structure of the actual framework and allow the developer to easily change that values of data without having to make a new page, or reload.  -->
```
<!-- So really I think I am confusing this with a different type of model view state or something. For me reading through it this was to clearest explination I could grasp. If there is a clearer reading that you know of, that would be amazing. -->

### Ember Concepts

What are the essential parts of an Ember 2 application?

```md
<!-- There are 5 essential parts of an ember app Routes, Models, Templates, Components, and Services. A route is the state of an application that is represented by a url which is controllers what the user sees. Every route has a model that is basically assigned to represent it, this provides the data that is to be displayed with application at the state the route is looking for. Templates are what is used to build the applications html and framework, HTMLBars which is another version of handlebars is used to build these templates. Components are used to implement behavior on an application, and its appearance is created using the templates referenced above. Finally services are just objects that hold data that will be carried over multiple sessions. -->
```

### Ember in Practice

In your own words, describe why someone would use Ember.

```md
<!-- Ember is great for applying multiple views to an application that change depending on the user interaction. It allows for a set up of templated out views that encorporate changable data and display the data appropriatly depending on what the value has been changed to. It also allows for the user to return to the view they have set up because when they return and log in, the componants in the URL will tell the model what to load into the template.  -->
```
<!-- I am not sure how accurate that is, or if I am even conveying my understanding correctly. However from what I read on the wiki and the examples they gave us on there, this is how I understood it. -->

### Ember and URLs

In your own words, how does Ember "stop breaking the web"?

```md
<!-- From what I took from the reading and the video, it stops breaking the web by applying components to URLs. What this does is allow for there to be a better way to sift through and apply nested views. It allows for multiple views to be displayed on top of each other, with different data values in each template being displayed. I don't know if that is at all accurate but that is how it broke down to me.  -->
```
