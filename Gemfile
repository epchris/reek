source 'https://rubygems.org'

gemspec

ruby RUBY_VERSION

group :development do
  gem 'activesupport',   '>= 4.2'
  gem 'aruba',           '~> 0.14.0'
  gem 'cucumber',        '~> 3.0'
  gem 'factory_bot',     '~> 4.0'
  gem 'kramdown',        '~> 1.17'
  gem 'rake',            '~> 12.0'
  gem 'rspec',           '~> 3.0'
  gem 'rspec-benchmark', '~> 0.3.0'
  gem 'rubocop',         '~> 0.58.0'
  gem 'rubocop-rspec',   '~> 1.20'
  gem 'simplecov',       '~> 0.16.1'
  gem 'yard',            '~> 0.9.5'

  platforms :mri do
    gem 'redcarpet', '~> 3.4.0'
  end
end

group :debugging do
  # Fixing https://github.com/guard/guard/wiki/Add-Readline-support-to-Ruby-on-Mac-OS-X#option-4-using-a-pure-ruby-readline-implementation
  gem 'pry'
  gem 'rb-readline', '~> 0.5.3'
  platforms :mri do
    gem 'pry-byebug'
    gem 'pry-stack_explorer'
  end
end
