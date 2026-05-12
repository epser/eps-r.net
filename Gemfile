source "https://rubygems.org"

# GitHub Pages 本番と同じバージョンの Jekyll とプラグインをまとめて入れる
# 対応バージョン: https://pages.github.com/versions/
gem "github-pages", group: :jekyll_plugins

# Windows / JRuby 用 tzinfo
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows でのファイル監視
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby 用
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
