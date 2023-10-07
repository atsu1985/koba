source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '7.1'
# Use postgresql as the database for Active Record
gem 'psql'
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# authenticate
gem 'devise'


# debug tools
group :development, :test do
  # pry
  gem 'pry-rails'          # rails cをpryに
  gem 'pry-doc'            # pryに show-doc(?), show-source($)コマンドを追加
  gem 'pry-byebug'         # binding.pry
  gem 'pry-stack_explorer' # pryにshow-stack等を追加

  # エラー画面系
  gem 'better_errors'
  gem 'binding_of_caller'

  # ActiveRecordの出力をテーブルに Hirb.disable/Hirb.enableで切り替えられる
  gem 'hirb'
  gem 'hirb-unicode'

  # print系
  gem 'awesome_print' # .apメソッド
  gem 'tapp' # .tappメソッドでオブジェクトの状態を出力
end

# rspec
group :test do
  gem 'rspec-rails', '~> 3.0'

  # matchers
  gem 'shoulda-matchers'
  gem 'test_xml', '~> 0.1.7'

end

# group :production, :staging do
gem 'puma'
# end
