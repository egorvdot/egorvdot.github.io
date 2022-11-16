source "https://rubygems.org"

gem "webrick", "~> 1.7"
gem "github-pages", "~> 227", group: :jekyll_plugins

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
