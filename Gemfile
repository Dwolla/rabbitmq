source 'https://rubygems.org'

gem 'chef', '>= 15.4.45'
gem 'chefspec', '>= 4.2.0'

group :lint do
  gem 'foodcritic', '>= 4.0.0'
  gem 'rubocop', '>= 0.49.0'
  gem 'rainbow'
end

group :unit do
  gem 'berkshelf', '>= 4.2.3'
  gem 'fauxhai', '>= 2.2.0'
end

group :kitchen_common do
  gem 'test-kitchen'
end

group :kitchen_vagrant do
  gem 'kitchen-vagrant'
end

group :kitchen_docker do
  gem 'kitchen-docker'
end

group :kitchen_cloud do
  gem 'kitchen-digitalocean', '>= 0.9.6'
  gem 'kitchen-ec2', '>= 0.8.0'
end

group :development do
  gem 'ruby_gntp'
  gem 'growl'
  gem 'rb-fsevent'
  gem 'guard', '>= 2.11.1'
  gem 'guard-kitchen', '>= 0.0.2'
  gem 'guard-foodcritic', '>= 1.0.3'
  gem 'guard-rspec', '>= 4.5.0'
  gem 'guard-rubocop', '>= 1.2.0'
  gem 'rake', '>= 12.3.3'
  gem 'stove'
end
