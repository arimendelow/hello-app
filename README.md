# Ruby on Rails tutorial HELLO app (with some snazzy additions!)

This is the first application for the [*Ruby on Rails Tutorial*](https://www.railstutorial.org/).

NOTES, for production (local use):
* Had to run `/usr/local/Cellar/postgresql/11.3//bin/createuser -s postgres` to create a user called `postgres` in order for the following command, which created the databases, to work:
* `bundle exec rake db:create:all`

This is in addition to installing postgresql locally, which is another seperate pain in the tuchas.

Also, don't forget to create a `.env` file with your `HELLO_APP_DATABASE_PASSWORD`. In order to create a random password, you can run `rake secret`.
