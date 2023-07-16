# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 6.1"
gem 'html-proofer', '3.19.4'
gem 'nokogiri', '1.15.3', platforms: [:ruby, :x64_mingw, :mingw, :mswin, :jruby]
gem 'parallel', '1.23.0'
gem 'rainbow', '3.1.1'
gem 'typhoeus', '1.4.0'
gem 'yell', '2.2.2'
gem 'racc', '1.7.1'
gem 'ethon', '0.16.0'

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Lock jekyll-sass-converter to 2.x on Linux-musl
if RUBY_PLATFORM =~ /linux-musl/
  gem "jekyll-sass-converter", "~> 2.0"
end
