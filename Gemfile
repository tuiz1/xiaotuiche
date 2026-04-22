# 国内镜像（可选）
source "https://mirrors.tuna.tsinghua.edu.cn/rubygems/"

# 建议 Ruby 版本（3.1 或 3.2 都可以）
ruby "3.2.11"

# ----------------------
# Jekyll 核心
# ----------------------
gem "jekyll", "~> 4.3.4"
gem "minima", "~> 2.5"

# ----------------------
# 官方推荐插件（GitHub Pages 兼容）
# ----------------------
gem "jekyll-feed", "~> 0.17"
gem "jekyll-seo-tag", "~> 2.8"
gem "jekyll-sitemap", "~> 1.4"

# ----------------------
# Windows 支持（必须）
# ----------------------
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# 时区支持（Windows 必需）
gem "tzinfo-data", :platforms => [:mingw, :x64_mingw, :mswin]

# ----------------------
# Markdown 解析
# ----------------------
gem "kramdown", "~> 2.4"
gem "kramdown-parser-gfm", "~> 1.1"

# ----------------------
# 开发工具（可选）
# ----------------------
group :development do
  gem "jekyll-admin"
  gem "jekyll-compose"
end