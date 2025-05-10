# RyanShang
cd ~/Projects
git clone https://github.com/szw744150138/szw744150138.github.io.git
cd szw744150138.
mkdir assets _data _includes _layouts zh en
mkdir -p assets/css
touch CNAME \
      assets/logo.png assets/cover.jpg \
      assets/css/style.css \
      _config.yml \
      _data/products.yml \
      _includes/header.html _includes/sidebar.html _includes/footer.html \
      _layouts/default.html \
      zh/index.md zh/products.md zh/contact.md zh/cooperation.md \
      en/index.md en/products.md en/contact.md en/cooperation.md.io
title: "纺织销售官网"
email: "744150138@qq.com"
description: "高品质纺织产品供应商"
baseurl: ""          
url: "https://szw744150138.github.io"

langs:
  - zh
  - en
default_lang: zh

exclude:
  - Gemfile
  - Gemfile.lock
  - node_modules/
  - vendor/

plugins:
  - jekyll-feed
  - jekyll-sitemap- id: 1
  name_zh: "纯棉布料"
  name_en: "Pure Cotton Fabric"
  price: "¥45/m"
  desc_zh: "柔软透气，适合夏季服装"
  desc_en: "Soft and breathable, ideal for summer wear"
# … 继续补充其他产品
- body { margin: 0; font-family: sans-serif; }
.site-header { display: flex; align-items: center; padding: 1rem; background: #f5f5f5; }
.logo { height: 40px; }
.main-nav a { margin: 0 1rem; text-decoration: none; color: #333; }
.lang-switch { margin-left: auto; }
.container { display: flex; }
.sidebar { width: 200px; padding: 1rem; background: #fafafa; }
.content { flex: 1; padding: 1rem; }
.site-footer { text-align: center; padding: 1rem; font-size: 0.9rem; background: #f5f5f5; }
