Step 1: Create a New Rails Project

To create a new Rails project, run:

rails new my_rails_project
cd my_rails_project

Step 2: Add RuboCop to the Project

Edit the Gemfile and add the following gems under the development and test groups:

group :development, :test do
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
end

Then install the gems:

bundle install

Step 3: Configure RuboCop