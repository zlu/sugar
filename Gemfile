source 'http://rubygems.org'
#source 'http://gems.github.com'

gem 'rails', '3.1.0'
gem 'capistrano'
gem 'mysql'

# OpenID gem. The stock gem is incompatible with Ruby 1.9, this fixes that.
gem 'ruby-openid', :git => 'git://github.com/xxx/ruby-openid.git', :require => 'openid'

gem 'hpricot'
gem 'daemon-spawn', '0.2.0'
gem 'newrelic_rpm'

gem 'delayed_job', '2.0.3'
gem 'thinking-sphinx', :git => 'git://github.com/freelancing-god/thinking-sphinx.git', :branch  => 'rails3', :require => 'thinking_sphinx'
gem 'ts-delayed-delta', '1.1.0', :require => 'thinking_sphinx/deltas/delayed_delta'

group :development do
      gem 'yui-compressor', :require => 'yui/compressor'
end

group :test do
      gem 'shoulda'
      gem 'factory_girl_rails'
end