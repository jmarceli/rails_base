# Ruby on Rails Base: base set of files for new application

This is meant to be package which allows to easily make a new application without worrying about installation of Rspec, Spork and Guard. It was made after a day of struggling with TDD approach shown in some Rails tutorials available on the web.
My plan is to update content of this repository as my knowledge about Ruby on Rails will grow.
This set was made on Virtualbox'ed Ubuntu 12.04 LTS.

## Known issues:

launchy gem is not installed because it somehow breaks Guard and hides Rspec messages.

## Development gems installed:

- capybara
- spork
- rspec
- guard
- guard-rspec
- guard-spork
- rename

## Download:

1. Open terminal
2. Go to the directory of your choice
3. Type inside terminal:

    git clone git://github.com/jmarceli/rails_base.git

4. Rename application to your_app_name by typing

    rails g rename:rails_base your_app_name


## Request for comments

If anyone saw something wrong inside this repo please report because as a beginner I probably made a few mistakes.
