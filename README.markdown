# Andru's Blog Engine

Setting up:

$ git clone git://github.com/andruu/blog-engine.git
$ cd blog-engine
$ bundle install
$ edit config/database.yml
$ rake db:create
$ rake db:migrate
$ rails console: create user with: User.create(email: 'your@email.com', password: 'yourpassword').save

## this shit works with shotgun, not sure why not with thin? Server issue?