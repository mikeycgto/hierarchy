source :rubygems

gem 'rails', '>= 3.0.2'

# Use platform specific gems
platforms :mri_20, :mri_19 do
  gem 'pg'
end

platforms :jruby do
  gem 'activerecord-jdbcpostgresql-adapter'
end

group :development do
  gem 'jeweler', require: nil
  gem 'yard', require: nil
  gem 'RedCloth', require: nil
  gem 'rspec'
end
