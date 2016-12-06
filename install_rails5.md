rbenv install 2.3.3
rbenv global 2.3.3
rbenv rehash
gem install bundle
 
echo "gem 'rails'" > Gemfile
bundle install --path vendor/bundle 

rails new . --api
