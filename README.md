# spree_nice_forms
This Spree extension adds floating labels to your Spree checkout forms and login/user forms. The extension uses pure css and some overrides to add uniformity to spree forms.

## Installation

1. Add the following extensions to the bottom of your Gemfile with this line:
  ``` ruby
  gem 'spree_nice_forms', github: 'matthewkennedy/spree_nice_forms'

  ```

2. Install the gem using Bundler:
  ```ruby
  bundle install
  ```

3. Copy & run migrations
  ```ruby
  bundle exec rails g spree_nice_forms:install
  ```

4. Restart your server

If your server was running, restart it so that it can find the assets properly.
