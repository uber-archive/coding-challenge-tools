Coding Challenge Guidelines
===========================

If you don't have code to share, you can work on our coding challenge described
below. 

Please organize, design, test, document and deploy your code as if it were
going into production, then send us a link to the hosted repository (e.g.
Github, Bitbucket...).

Functional spec
---------------

Prototype **one** of the following projects:

1. Departure Times
2. SF Movies
3. Email Service
4. Food Trucks

The UX/UI is totally up to you. If you like, get creative and add additional
features a user might find useful!

### Departure Times

Create a service that gives real-time departure time for public transportation
(use freely available public API). The app should geolocalize the user.

Here are some examples of freely available data:

* [511](http://511.org/developer-resources_transit-api.asp) (San Francisco)
* [Nextbus](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) (San
  Francisco)
* [Transport for London Unified API](https://api.tfl.gov.uk/) (London)

### SF Movies

Create a service that shows on a map where movies have been filmed in San
Francisco. The user should be able to filter the view using autocompletion
search.

The data is available on [DataSF](http://www.datasf.org/): [Film
Locations](https://data.sfgov.org/Arts-Culture-and-Recreation-/Film-Locations-in-San-Francisco/yitu-d5am).

### Email Service

Create a service that accepts the necessary information and sends emails. It
should provide an abstraction between two different email service providers.
If one of the services goes down, your service can quickly failover to
a different provider without affecting your customers.

Example Email Providers:

* [SendGrid](https://sendgrid.com/user/signup) - [Simple Send Documentation](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
* [Mailgun](http://www.mailgun.com) - [Simple Send Documentation](http://documentation.mailgun.com/quickstart.html#sending-messages)
* [SparkPost](https://www.sparkpost.com/) - [Developer Hub](https://developers.sparkpost.com/)
* [Amazon SES](http://aws.amazon.com/ses/) - [Simple Send Documentation](http://docs.aws.amazon.com/ses/latest/APIReference/API_SendEmail.html)

All listed services are free to try and are pretty painless to sign up for, so
please register your own test accounts on each.

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

Choose **one** of the following technical tracks that best suits your skillset:

1. **Full-stack**: include both front-end and back-end.
2. **Back-end track**: include a minimal front-end (e.g. a static view or API
   docs). Write, document and test your API as if it will be used by other
   services.
3. **Front-end track**: include a minimal back-end, or use the data service
   directly. Focus on making the interface as polished as possible.

### Back-end

We believe there is no one-size-fits-all technology. Good engineering is about
using the right tool for the right job, and constantly learning about them.
Therefore, feel free to mention in your `README` how much experience you have
with the technical stack you choose, we will take note of that when reviewing
your challenge.

Here are some technologies we are more familiar with:

* Python
* JavaScript
* Ruby
* PHP
* Go
* C++
* Haskell
* Java

You are also free to use any web framework. If you choose to use a framework
that results in boilerplate code in the repository, please detail in your
README which code was written by you (as opposed to generated code).

### Front-end

The front-end should ideally be a single page app with a single `index.html`
linking to external JS/CSS/etc. You may take this opportunity to demonstrate
your CSS3 or HTML5 knowledge.

Host it!
--------

When you’re done, host it somewhere (e.g. on Amazon EC2, Heroku, Google AppEngine, etc.).

How will we review?
-------------------

[Guidelines can be found here](https://github.com/uber/coding-challenge-tools/blob/master/README.md)
