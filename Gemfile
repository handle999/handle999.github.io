source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]    # need this one. add

gem "github-pages", "228", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

gem "webrick"           # must add
gem "jekyll", "3.9.3"   # control version. 3.9.4 is not allowed
# Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'
# E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/rubyeventmachine.rb:2:in `require': cannot load such file -- 3.0/rubyeventmachine (LoadError)
gem 'eventmachine', github: 'eventmachine/eventmachine'   # use github version

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end
