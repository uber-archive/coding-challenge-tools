Web Coding Challenge
====================

Here is a sample project that will give us some insight into your current level
of experience.

This is a simple project, but organize, design, test and document your
code as if it were going into production. Please then send us:

* A link to the hosted application (e.g. Amazon EC2, Heroku, etc.)
* A link to the hosted repository (e.g. Github/Bitbucket)

Write your README as if it was for a production service, and include the
following items:

* The project you chose (departure times, SF movies, bicycle parking *or* food
  trucks)
* The technical track you chose (full stack, back-end *or* front-end)
* Reasoning behind your technical choices (and level of experience with those)
* Link to other code you're particularly proud of
* Link to your resume or public profile

Functional spec
---------------

Prototype **one** of the following projects:

1. Departure Times
2. SF Movies
3. Bicycle Parking
4. Food Trucks

Spend as much time as you like on this. However, out of respect for your time,
if you need to scope it to 3-4 hours, feel free to mock/fake any feature that
you don't have time to develop.

The UX/UI is totally up to you. Feel free to explain any assumptions you have
to make. If you like, get creative and add additional features a user might
find useful! 

### Departure Times

Create a service that gives real-time departure time for public transportation
(use freely available public API). The app should geolocalize the user.

Here are some examples of freely available data:

* [511](http://511.org/developer-resources_transit-api.asp) (San Francisco)
* [Nextbus](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) (San
  Francisco)

### SF Movies

Create a service that shows on a map where movies have been filmed in San
Francisco. The user should be able to filter the view using autocompletion
search.

The data is available on [DataSF](http://www.datasf.org/): [Film
Locations](https://data.sfgov.org/Arts-Culture-and-Recreation-/Film-Locations-in-San-Francisco/yitu-d5am).

### Bicycle Parking

Create a service providing directions to the nearest bicycle parking.

The data is available on [DataSF](http://www.datasf.org/): [Bicycle
Parking](https://data.sfgov.org/Transportation/Bicycle-Parking-Public-/w969-5mn4) 

### Food Trucks

Create a service that tells the user what types of food trucks might be found
near a specific location on a map.

The data is available on [DataSF](http://www.datasf.org/): [Food
Trucks](https://data.sfgov.org/Permitting/Mobile-Food-Facility-Permit/rqzj-sfat) 

Technical spec
--------------

The architecture will be split between a back-end and a web front-end, for
instance providing a JSON in/out RESTful API. Feel free to use any other
technologies provided that the general client/service architecture is
respected.

Choose **one** of the following technical track:

1. **Full-stack**: include both front-end and back-end.
2. **Back-end track**: include a minimal front-end. Write, document and test
   test your API as if it will be used by other services and front-ends.
3. **Front-end track**: include a minimal back-end, or use the data service
   directly. Focus on making the interface as polished as possible.

### Back-end

We believe there is no one-size-fits-all technology. Good engineering is about
using the right tool for the right job. A big part of what we do is learning
new tools and technologies. Therefore, feel free to mention in your `README`
how much experience you have with the technical stack you choose, we will take
note of that when reviewing your challenge.

Here are some technologies we are more familiar with:

* **Python** (most of our back-end uses this language)
* JavaScript
* Ruby
* PHP
* Go
* C++
* Haskell
* Java

You are also free to use any web framework, although we would prefer that you
use a microframework (e.g. [Flask](http://flask.pocoo.org/)) and stay away from
large frameworks like Django, Ruby on Rails, etc. Those will not give us as
good insights into your skills.

### Front-end

The front-end should ideally be a single page app with a single `index.html`
linking to external JS/CSS/etc. You may take this opportunity to demonstrate
your CSS3 or HTML5 knowledge.

We recommend using [Backbone.js](http://documentcloud.github.com/backbone/)
for front-end MVC.

Host it!
--------

When you’re done, host it somewhere and provide us with the server's URL, as
well as a public URL for the repository hosting your code.
