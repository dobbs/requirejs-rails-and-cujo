requirejs-rails and cujo
========================

how I got this started

    rvm use ruby-1.9.2-p318@requirejs-rails-and-cujo --create
    gem install rails --version 3.2.10 --no-rdoc --no-ri
    rails new --skip-test-unit --skip-active-record requirejs-rails-and-cujo
    cd requirejs-rails-and-cujo
    rvm use ruby-1.9.2-p318@requirejs-rails-and-cujo --rvmrc
    rvm rvmrc trust .
    echo "gem 'requirejs-rails'" >> Gemfile
    bundle install