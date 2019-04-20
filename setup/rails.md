 # `rails new`
  -  `--database=postgresql` if using Postgres.
  - `--skip-turbolinks` to skip turbolinks gem

# `gems`
  - `better_errors`
  - `binding_of_caller`
  - `pry-rails`
  - `annotate`
  - `bcrypt`
  - `jquery-rails` (When using rails 5.1+)
  - `jbuilder`

### `gem install better_errors binding_of_caller pry-rails annotate bcrypt jquery-rails jbuilder`

# Rails 5.1+, update application.js manifest to include:
  - `//= require jquery`
  - `//= require jquery_ujs`