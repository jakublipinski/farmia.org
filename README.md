# brew install ruby
# export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
# sudo gem install bundler -v 3.2.3
# bundle install

bundle config set --local path 'vendor/bundle' 
bundle exec jekyll serve --livereload