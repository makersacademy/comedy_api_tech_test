# Comedy API Tech Test

Show your REST API skills developing a single page app to work with a Comedy API.

There are not that many Joke APIs available.  There is a long-standing Chuck Norris Joke API:

http://www.icndb.com/api/

Which is great until you get sick of Chuck Norris Jokes.

Brief
-----

To design a new website for the Comedy Store.  The Comedy Store Marketeers are demanding that the website include a new and different joke every time a guest visitor visits the site.  To the extent the guest visitor can be identified (by cookie etc.) the same joke should not be displayed twice (up to the limit of the jokes available).  They would also like users to be able to log in, in order to '+1' individual jokes. Users who are logged in should be able to browse the range of jokes and '+1' as appropriate.  The list of jokes should then also be sortable in both directions by votes.

The site should display dates of upcoming comedy store events (make some up or grab some from the [real comedy store site](http://thecomedystore.co.uk/)) and a custom joke at the top of the page.

Use the Chuck Norris Joke API to get random jokes for a first prototype.  Then develop your own RESTful joke API to increase the range of possible jokes.  Follow the base operation of the Chuck Norris joke API, but extend as appropriate.

You are free to use any front end and back end technologies that you prefer.  You're solution will be judged on clean separation of concerns, effective use of TDD, BDD and OOD techniques.

Ensure that your solution is a responsive single page app that can be easily switched between different joke APIs.

Bonus Level
-----------

Set up CI with [Travis](https://travis-ci.org/), [Hound](https://houndci.com/) and [Coveralls](https://coveralls.io/) on your git repo.
