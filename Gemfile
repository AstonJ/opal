source :rubygems
gemspec

gem "rake"

# for rebuilding grammar.rb from grammar.y
group :grammar do
  gem "racc"
end

# running tests on command line
group :testing do
  gem 'opal-spec', :git => 'git://github.com/opal/opal-spec.git'
end