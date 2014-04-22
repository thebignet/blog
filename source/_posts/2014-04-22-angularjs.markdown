---
layout: post
title: "The battle of modern javascript frameworks"
date: 2014-04-22 18:52:52 +0200
comments: true
categories: ['angularjs','javascript']
---

In 2012 I started looking at the effusion of JS frameworks, amongst which three cought my attention :

* [Backbone.js](http://backbonejs.org/)
* [Knockout.js](http://knockoutjs.com/)
* [AngularJS](angularjs.org)

At that time, **AngularJS** was still emerging compared to Backbone, which was used in production and had all the attention.  Backbone is simple, so simple that its code serves as documentation.  This seems like a good thing, but the purpose of a framework is not to be designed simply, but to be simple to use.  That's what Knockout.js and AngularJS are.  But between the two, Knockout.js is too limited.  It does very well with data binding and templating, but doesn't have advanced features that made the popularity of AngularJS such as dependency injection, services, directives, animations ...

AngularJS is my prefered choice for future web applications.  It does wonders with a backend thanks to its REST API.  For me there's no need to have server-side rendering as AngularJS can take care of it and make use of services to communicate to the server.

Comparison between frameworks
----

The following characteristics are not meant to be exhaustive, but are of prime order to me regarding JavaScript frameworks.

Characteristic | AngularJS | Backbone.js | Knockout
--- | :---: | :---: | :---:
Ease of learning | 3 | 2 | 1
Documentation | 1 | 2 | 3
Community | 1 | 2 | 3
[Number of users](http://www.google.com/trends/explore?hl=en-US#q=Angularjs%2C%20Backbone.js%2C%20Knockout.js&date=today%2012-m&cmpt=q) | 1 | 2 | 3
Testing | <i class="fa fa-check"></i> | <i class="fa fa-check"></i> | <i class="fa fa-check"></i>
Dependency injection | <i class="fa fa-check"></i> | <i class="fa fa-check"></i> | 
Flexibility (1) | 3 | 1 | 2
Convention | 1 | 3 | 2
**One** way data binding | <i class="fa fa-check"></i> | with epoxy.js | <i class="fa fa-check"></i>
**Two** way data binding | <i class="fa fa-check"></i> | with epoxy.js | <i class="fa fa-check"></i>
Level of separation from DOM | 1 | 3 | 2
Extendability | 1 | 2 | 3


Ordering is from best to last

(1) AngularJS is noted as less flexible, but that is because it follows conventions.  This is what makes it more efficient than other frameworks.  The structure and convention is set, leaving way for the app's code.  There's no need to reinvent the wheel, nor to ensure certain standards that one has to maintain between developers.

AngularJS is great for medium to large projects if you follow simple conventions.  There's just no bending the model as you would in Backbone and Knockout.  But overall, it's for the best.  Here's how it's meant to be used :

Service : Connectors to external APIs
Directive : Allows to modify DOM through the use of tags or attributes and bind to scope
View : DOM
Controller : Glue between Scope and other components like Services//Directives