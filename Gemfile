source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"
gem "webrick", "~> 1.7"
gem "jekyll-feed", "~> 0.15.1"

group :jekyll_plugins do
  gem "jekyll-feed"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
