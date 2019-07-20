# jekyll_personal_blog
This is a jekyll personal blog demo


# how to build this web site

## prepare ruby(mac os)

```
brew install ruby
export PATH=/usr/local/Cellar/ruby/2.6.3/bin/:$PATH
gem env

ruby -v
ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-darwin16]
```

gem update
```
$ gem update --system # 这里请翻墙一下
$ gem -v
2.6.3

$ gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
$ gem sources -l
https://gems.ruby-china.com # 确保只有 gems.ruby-china.com
```

## install jekyll

```
gem install jekyll
export PATH=/usr/local/lib/ruby/gems/2.6.0/gems/jekyll-3.8.6/exe:$PATH
```

## new blog

```
jekyll new qiuwenqi

cd qiuwenqi

jekyll serve --host 0.0.0.0 --port 4000

curl 127.0.0.1:4000
```



