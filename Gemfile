if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'puma'
gem 'pg'
gem 'devise'
gem 'carrierwave'
gem 'rmagick'
gem 'letsrate'
gem 'cancan'
gem 'omniauth'
gem 'omniauth-oauth2'
gem 'omniauth-facebook'
gem 'nokogiri'
gem 'will_paginate'
gem 'tire'
gem 'moip', git: 'git://github.com/pitagg/moip-ruby.git',
            ref: '40ff0176f9acc96c45779d0ba6a288bc6ef642cc'
gem 'httparty'

gem 'daemons'
gem 'delayed_job_active_record'

gem 'rack-ssl-enforcer'

#gem para automatizar tarefa de verificação de interações pendentes
gem 'whenever', :require => false

#GEM's para criação e exportação para EXCEL (XSL)
gem 'spreadsheet', '~> 1.1'
gem 'to_xls', '~> 1.5'
#

#SEO
gem 'meta-tags'
gem 'friendly_id'

gem 'jquery-fileupload-rails'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'haml'
gem 'haml-rails'
gem 'excon' #dependencia fog
gem 'fog' #dependencia engines
gem 'aasm'
gem 'pismo' #metadata de págninas(títulos, etc.)
gem 'simple_form'
gem 'mustache', '< 1.0' #logic-less templates
gem 'poirot' #mustache no servidor e no cliente
gem 'paper_trail' #versionamento dos registros importantes
gem 'brazilian-rails' #recursos úteis para desenvolvedores brasileiros.

group :test do
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'spork'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'simplecov'
  gem 'rb-fsevent', '~> 0.9.1'
end

group :development, :staging, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'factory_girl-preload'
  gem 'faker'
  gem 'debugger-ruby_core_source'
  gem 'debugger'
  gem 'ruby-debug-passenger'
end
