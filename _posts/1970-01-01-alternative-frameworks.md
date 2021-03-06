---
layout: post
title: Alternative frameworks
order: 50
---

The Ruby ecosystem does not end at Ruby on Rails. There are a number of alternative frameworks which excel in different areas or provide a more lightweight way to build web apps.
Here are some of the most notable:
 
## Full-featured

### [Hanami.rb](http://hanamirb.org/)

Hanami proposes a cleaner approach with less metaprogramming than Rails. Some interesting architectural decisions are: multi-app architecture with shared parts (that delays and simplifies the decision to break your app into smaller parts), data mapper/entity-repository approach for the persistence layer, separated actions, explicit exposition of variables for views, and more.

* [What is Hanami? Where is it going?](https://discuss.hanamirb.org/t/what-is-hanami-where-is-it-going/222)

## Specialized 

### [Grape](http://www.ruby-grape.org/)

Grape is an opinionated framework for creating REST-like APIs in Ruby. It has built-in support for common conventions, including: multiple formats, subdomain/prefix restriction, content negotiation, versioning, and much more. All these elements are described via a simple DSL.
 
## Mini

The Mini framework focuses on providing a web request routing layer and leaves everything else to us. All Ruby web frameworks support, or are based on, Rack - a minimal interface for Ruby webservers, which standardizes how web requests are handled. Rack allows us to create a chain of "middlewares" (small specific handlers) that give us many basic things such as variable parsing, cookie and session management, etc – things that we tend to consider as a "given."

* [dry-web](https://github.com/dry-rb/dry-web)
* [Padrino](http://padrinorb.com/)
* [Rack](http://rack.github.io/)
* [Roda](http://roda.jeremyevans.net)
* [Sinatra](http://www.sinatrarb.com/)
