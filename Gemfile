source 'https://rubygems.org'

# gem "github-pages", '163', group: :jekyll_plugins
# The github-pages meta-gem is not used because it pins jekyll-remote-theme
# 0.4.3, which locks rubyzip < 3.0 (path traversal vulnerability). Instead we
# list only the gems this site needs, matching what GitHub Pages provides.
gem "jekyll", "~> 3.10"
gem "kramdown-parser-gfm", "~> 1.1"

group :jekyll_plugins do
  gem "jekyll-sitemap", "~> 1.4"
  # Plugins GitHub Pages enables by default
  gem "jekyll-github-metadata", "~> 2.13"
  gem "jekyll-optional-front-matter"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
  gem "jekyll-relative-links"
  gem "jekyll-readme-index"
end

# enable tzinfo-data for local build
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
gem 'jekyll-paginate'

gem "kramdown", ">= 2.3.1"
gem "commonmarker", ">= 0.23.4"
gem "nokogiri", ">= 1.13.4"
gem "activesupport", ">= 6.1.7.1"

gem "webrick", ">= 1.8.2"
gem "rexml", ">= 3.2.8"
