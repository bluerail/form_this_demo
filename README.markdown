Demo Rails application for [Form This!](https://github.com/bluerail/form_this).

You can start it with:

    cd demo
    bundle install --path vendor/bundle
    bundle exec rake db:migrate
    bundle exec rails server

And then go to [http://localhost:3000](http://localhost:3000). The interesting
files to look at are in [`app/forms/`](app/forms/).
