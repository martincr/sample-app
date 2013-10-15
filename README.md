# Ruby on Rails Tutorial: sample application

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.

rails new sample_app --skip-test-unit
bundle install --without production
Post-install message from capybara:
IMPORTANT! Some of the defaults have changed in Capybara 2.1. If you're experiencing failures,
please revert to the old behaviour by setting:

    Capybara.configure do |config|
      config.match = :one
      config.exact_options = true
      config.ignore_hidden_elements = true
      config.visible_text_only = true
    end

If you're migrating from Capybara 1.x, try:

    Capybara.configure do |config|
      config.match = :prefer_exact
      config.ignore_hidden_elements = false
    end

Details here: http://www.elabs.se/blog/60-introducing-capybara-2-1
rails generate rspec:install
git init
git add .
git commit -m "Initial commit"


git commit -a -m "Improve the README"