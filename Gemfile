source "https://rubygems.org"

# Mirror GitHub Pages' build environment
gem "github-pages", group: :jekyll_plugins

# Live reload during local dev
group :jekyll_plugins do
  gem "jekyll-livereload"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem
# (harmless on Linux, speeds up GH Pages parity checks)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
