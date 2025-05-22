在mac上用 bundle exec jekyll serve 运行预览,然后undle exec jekyll build得到_site文件,再用cloudflare来deploy _site
p.s.  bundle exec jekyll build -d /Users/kkchen/Documents/GitHub/kefan-page

在cloudflare加变量
RUBY_VERSION = "2.7.8"
BUNDLER_VERSION = "2.1.4"
