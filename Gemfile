source "https://rubygems.org"

# Use GitHub Pages gem for compatibility with GitHub Pages
gem "github-pages", group: :jekyll_plugins


# If you want to use a custom theme, replace "minima" with your theme of choice
gem "minima", "~> 2.0"

# Development tools
group :development do
  gem "jekyll"
  gem "ruby-lsp"                   # Language Server Protocol for Ruby
end

# Plugins for Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"       # RSS feed for your blog
  gem "jekyll-seo-tag"             # SEO metadata
  gem "jekyll-sitemap"             # Sitemap for search engines
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Markdown parser for GitHub Flavored Markdown
gem "kramdown-parser-gfm"

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]