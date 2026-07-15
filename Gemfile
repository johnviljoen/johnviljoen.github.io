source "https://rubygems.org"

# Use the github-pages gem so your local build matches GitHub Pages exactly.
gem "github-pages", group: :jekyll_plugins

# Plugins (kept in sync with _config.yml)
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

# Windows / JRuby compatibility shims (harmless elsewhere)
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "wdm", "~> 0.1.1", platforms: [:mingw, :mswin, :x64_mingw]

# Fixes a webrick dependency dropped from Ruby 3.0+
gem "webrick", "~> 1.8"
