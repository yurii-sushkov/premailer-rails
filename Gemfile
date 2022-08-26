# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

rails_version = ENV.fetch('ACTION_MAILER_VERSION', '6')

# if rails_version == 'master'
  # git 'git://github.com/rails/rails.git' do
  gem 'rails', '6.1.4.4'
  # end
  gem 'arel', github: 'rails/arel'
  gem 'sprockets-rails', github: 'rails/sprockets-rails'
# else
#   gem 'rails', "~> #{rails_version}"
# end

gem 'byebug'

# platforms :rbx do
#   gem 'racc'
#   gem 'rubysl'
# end

gem 'tins', '< 1.7' if RUBY_VERSION.split('.').first.to_i < 2
