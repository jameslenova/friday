source 'http://rubygems.org'

#gem 'rails', '3.0.9'
gem 'rails', '3.1.1'
#gem 'rinku', '~> 1.2.2', :require => 'rails_rinku'

gem 'rinku', :require => 'rails_rinku'
gem 'bundler', '~> 1.0.17'


gem 'simple_form', '1.5.1'
gem 'jquery-rails', '1.0.14'
#gem 'mysql2', '~> 0.3.7'
#gem "mysql2", "0.3.7"
#gem 'pg'

gem 'sqlite3', '~> 1.3.5', :platform => 'ruby'
gem 'mysql2', '~> 0.3.7'


platform :ruby do
  #gem 'mysql2', '~> 0.2.7'
 gem 'mysql2', '~> 0.3.7'
  gem 'unicorn'
end

platforms :jruby do
  gem 'activerecord-jdbc-adapter'
  gem 'jruby-openssl'
  gem 'jdbc-mysql', :require => false
  gem 'jdbc-sqlite3', :require => false
  gem 'trinidad'
end




# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do



#group :assets do
 # gem 'sass-rails',   '~> 3.1.4'
  #gem 'coffee-rails', '~> 3.1.1'
#  gem 'uglifier', '>= 1.0.3'
#end



end
