== README

#Sample Unicorn Rails Application

* Version

Ruby 2.0.0-p353
Rails 4.0.0

* System dependencies

sqliste-devel(centos)
sqlite3 gem

* Usage

Justo only run this code.

    cd /path/to/app
    RAILS_ENV=production rake deploy:start

Database(sqlite3) and assets are setupped and start unicorn server on port 3000.
see http://localhost:3000

Stop server.

    rake unicorn:stop

