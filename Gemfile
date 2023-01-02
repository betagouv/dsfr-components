source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Declare your gem's dependencies in govuk-components.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use a debugger
# gem 'byebug', group: [:development, :test]

# until https://github.com/nanoc/nanoc/issues/1639 is fixed
gem "nanoc", github: 'betagouv/nanoc', branch: 'fix/haml-filter'

group 'nanoc' do
  gem 'nanoc-live'
end

gem "rubocop-rspec", "~> 2.14"
