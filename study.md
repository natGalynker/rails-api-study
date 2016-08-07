# Rails as an API Study

Use your favorite search engine and the provided readings to research and answer
the following questions (no prior knowledge is expected).

In your answers, be sure to cite any relevant sources you consulted in your
search. We ask you to write answers in your own words in order to see how you
process what you've read. Please do not answer with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Please note:

-   Many of the readings will mention the "view" layer. We won't be covering the
    view layer in this program.
-   We'll use our [rails-api-template](https://github.com/ga-wdi-boston/rails-api-template)
    repository as the basis for our rails applications.
    This template excludes the "view" layer.

## Required Readings

-   [Starting Ruby on Rails: What I Wish I Knew | BetterExplained](http://betterexplained.com/articles/starting-ruby-on-rails-what-i-wish-i-knew/)
-   [Intermediate Rails: Understanding Models, Views and Controllers | BetterExplained](http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/)
-   [Getting Started with Rails — Ruby on Rails Guides](http://guides.rubyonrails.org/getting_started.html)
-   [The Rails Command Line — Ruby on Rails Guides](http://guides.rubyonrails.org/command_line.html)
-   [Rails Routing from the Outside In — Ruby on Rails Guides](http://guides.rubyonrails.org/routing.html)
-   [Action Controller Overview — Ruby on Rails Guides](http://guides.rubyonrails.org/action_controller_overview.html)

## Define Model Responsiblities

In your own words, define what the responsibilities of the model layer are in
Rails.

```md
Models are the classes which hold all the data. They hold most of the information
so that the controllers don't have to hold much and can just perfrom the actions
on the data. These models are what all the actions are being done on, so it is
a lot of data to hold. The objects and classes we have been learning about in
Ruby is what would be going into the model layer.
```

## Define Controller Responsiblities

In your own words, define what the responsibilities of the controller layer are
in Rails.

```md
The responsibilities of the controller is primarily handling all the server
actions and calls. It collects the data from the Model and takes that data,
doing something with it actions wise(methods) and submits the request of that
action to the browser.
```

## Define Router Responsiblities

In your own words, define what the router does in Rails.

```md
The router is the thing which handles api calls, just like in javascript ajax handled
the API calls. When the server receives a request from the controller, the
router does something with that request, whether it is getting information from it.
Also known as CRUD requests or Create, Read, Update, and Delete.
```

## The Request-Response Cycle in Rails

Starting with a client making a GET request to a particular URL, describe how
the parts of Rails interact to produce and send a response.

```md
Route will reate the paths which will handle the Get request to that URL. The
the request to retrive the GET request for data will only be completed if the path
in the routes file matches up accordingly. It then finds the matching action, from
the cotroller and make the request call. During the call it will store the data
from that request in the params hash/directory
```
