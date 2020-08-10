# Summary of Read 07

## How I explained REST to my bother
A webpage is a representation of a resource. </br>

API can mean a lot of things to a lot of different people, but it essentially is a way for the web to communicate just like people do.</br>

Machines talking to machines about other machines -- redirect </br>

Think of a URL as a machines noun </br>

polymorphism -- different nouns can have the same very applied to them. i.e. request.get('XXX') or URL.get('XXX'), different nouns but the same verb and concept being applied to both. </br>

HTTP is a general purpose protocol for applying verbs to nouns </br>

Ruby on Rails is a RESTful framework </br>

## SuperAgent Docs
light-weight progressive API for flexibility, readability and help with a low learning curve. Formatted like a chained `.then()` request. Seems to be very readable which is helpful because I don't understand much when it comes to API's. This will be helpful for getting a hang of it. 

We can `.get()`, `.set()`, `.send()`, `.post()` and more with SuperAgent. In pokedex we just used request I believe. 

The Doc goes in depth into all the different methods that can be used with request. This will be a good reference this week when I need to read about what certain chain methods are doing and how to use them!