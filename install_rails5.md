```
mkdir my_app
echo "source 'https://rubygems.org'\ngem 'rails'" > Gemfile
bundle install --path vendor/bundle
bundle exec rails new . --api
```
