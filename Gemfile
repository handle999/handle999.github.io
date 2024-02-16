# frozen_string_literal: true

# 原来是https://rubygems.org/，会报错，所以改用国内镜像
source "https://gems.ruby-china.com/"

gemspec

# 各种报错没有webrick，所以加上这个依赖（相当于import？）
# 这些也是参照github的说明，以及报错查询
gem "faraday-retry"
gem "github-pages", group: :jekyll_plugins
gem "jekyll", "3.9.5"
gem "wdm", ">= 0.1.0" if Gem.win_platform?
gem "webrick"


# 好了，现在可以运行了，执行如下命令即可
# bundle exec jekyll serve
# 然后在localhost:4000查看网页
