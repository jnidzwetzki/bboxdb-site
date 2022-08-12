# BBoxDB org website
Source of the https://bboxdb.org website

```shell
apt-get install ruby-dev ruby-bundler

gem install --user-install bundler
gem install --user-install jekyll

# Syntax highlight
gem install --user-install kramdown rouge
rougify style github > assets/css/syntax.css

bundle config set --local path 'vendor/bundle'
bundle install

export PATH=$PATH:~/.local/share/gem/ruby/2.7.0/bin

bundle exec jekyll serve
bundle exec jekyll serve --host=0.0.0.0
```

