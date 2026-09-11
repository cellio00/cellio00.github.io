source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool'

# github-pages' jekyll-mentions -> html-pipeline doesn't pin activesupport,
# so an unlocked install grabs the latest (8.x), which needs a minitest/prism
# combo that won't resolve. Pin below 8 to stay on the minitest ~> 5.1 line.
gem 'activesupport', '< 8'
