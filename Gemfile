source "https://rubygems.org"

# Jekyll version
gem "jekyll", "~> 4.3.0"

# Theme
gem "minima", "~> 2.5"

# Required for Ruby 3.4+
gem "csv"
gem "logger"
gem "base64"
gem "bigdecimal"
gem "rexml"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
