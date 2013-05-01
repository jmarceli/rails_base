# Ruby on Rails Base: base set of files for new application

This is meant to be package which allows to easily make a new application without worrying about installation of Rspec, Spork and Guard. It was made after a day of struggling with TDD approach shown in some Rails tutorials available on the web.
My plan is to update content of this repository as my knowledge about Ruby on Rails will grow.
This set was made on Virtualbox'ed Ubuntu 12.04 LTS.

Known issues: 
launchy gem is not installed because it somehow breaks Guard and hides Rspec messages.

Development gems installed:
- capybara
- spork
- rspec
- guard
- guard-rspec
- guard-spork