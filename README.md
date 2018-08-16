I built this sample application by following along with the tutorial listed below. You can check out my completed, deployed version on Heroku [here](https://pacific-forest-82211.herokuapp.com/)

It is a social app modeled after Twitter, which allows users to post microposts and follow/unfollow other users.

It was a good exercise in test-driven development, something that was relatively new to me. This took me a little over a month to complete, and I worked about an hour or so per day. 

# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
