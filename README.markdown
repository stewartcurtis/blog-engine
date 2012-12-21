<<<<<<< HEAD
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
=======
# Dizz Diamond's Blog Engine

Setting up:

    $ git clone git://github.com/andruu/blog-engine.git
    $ cd blog-engine
    $ bundle install
    $ edit config/database.yml
    $ rake db:create
    $ rake db:migrate
    $ rails console # create user with: User.create(email: 'your@email.com', password: 'yourpassword').save

^^
# bugs
/admin doesn't work with thin on my computer but works with shotgun.

>>>>>>> 2316baf3527206dfd376d3f91f4402ea63477d72
