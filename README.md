# require
Virtual Box
Vagrant
$ vagrant up
$ vagrant ssh-config --host melody >> ~/.ssh/config

# rbenv
rbenv install 2.1.1
rbenv rehash

# ruby

# bundler
gem install bundler
## install gem
bundle install --path=vendor/bundle
## update gem
bundle update

# example
## create site cookbook
$ bundle exec knife cookbook create iptables -o site-cookbooks
## download vendor cookbook
$ bundle exec knife cookbook site vendor yum-epel

# execute
bundle exec knife solo cook melody

