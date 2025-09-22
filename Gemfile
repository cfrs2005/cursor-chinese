source "https://rubygems.org"

# Jekyll 和 GitHub Pages
gem "github-pages", group: :jekyll_plugins
gem "jekyll", "~> 3.9.0"

# Just the Docs 主题
gem "just-the-docs"

# Jekyll 插件
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-github-metadata"
  gem "jekyll-include-cache"
end

# Windows 和 JRuby 平台支持
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 性能优化
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby HTTP 客户端
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
