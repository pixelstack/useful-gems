# Useful Gems

## Authentication

**authorization and ACL:**
```
gem 'cancan'
```

[view on github](https://github.com/ryanb/cancan) | [view on RubyGems](https://rubygems.org/gems/cancan) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/cancan)

**Authorization Gem for Ruby on Rails with administrative interface. Semantic, Flexible, Lightweight (Competitor to Can-Can):**
```
gem 'the_role'
```

[view on github](https://github.com/the-teacher/the_role) | [view on RubyGems](http://rubygems.org/gems/the_role) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/the_role)

**full on authorisation:**
```
gem 'devise'
```

[view on github](https://github.com/plataformatec/devise) | [view on RubyGems](http://rubygems.org/gems/devise) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/devise)

**used for invitation based devise stuff, works with devise:**
```
gem 'devise_invitable'
```
[view on github](https://github.com/scambra/devise_invitable) | [view on RubyGems](http://rubygems.org/gems/devise_invitable) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/devise_invitable)

**Use alternative (and even your own!) encryptors with Devise.**
```
gem 'devise-encryptable'
```
[view on github](https://github.com/plataformatec/devise-encryptable) | [view on RubyGems](http://rubygems.org/gems/devise-encryptable) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/devise-encryptable)

**Rails authentication with email & password.**
```
gem 'clearance'
```
[view on github](https://github.com/thoughtbot/clearance) | [view on RubyGems](http://rubygems.org/gems/clearance) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/clearance)

**general authentication:**
```
gem 'authlogic'
```
[view on github](https://github.com/binarylogic/authlogic) | [view on RubyGems](http://rubygems.org/gems/authlogic) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/authlogic)

**multiple authentication methods:**
```
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-google'
```

**Taint and required checking for Action Pack and enforcement in Active Model *(should be in Rails 4 Core):**
```
gem 'strong_parameters'
```
[view on github](https://github.com/rails/strong_parameters) | [view on RubyGems](http://rubygems.org/gems/strong_parameters) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/strong_parameters)

**Signed forms for your Ruby On Rails app:**
```
gem 'signed_form'
```
[view on github](https://github.com/erichmenge/signed_form) | [view on RubyGems](http://rubygems.org/gems/signed_form) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/signed_form)

**Ruby gem for interacting with the AlterEgo API:**
```
gem 'alterego'
```
[view on github](https://github.com/tatemae-consultancy/alterego) | [view on RubyGems](http://rubygems.org/gems/alterego) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/alterego)


**used for multi-tenancy application work, eg basecamp style, multi users one account.:**
```
gem 'acts_as_tenant'
```
[view on github](https://github.com/ErwinM/acts_as_tenant) | [view on RubyGems](http://rubygems.org/gems/acts_as_tenant) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/acts_as_tenant)

**Database multi-tenancy for Rack (and Rails) applications:**
Apartment provides tools to help you deal with multiple databases in your Rails application. If you need to have certain data sequestered based on account or company, but still allow some data to exist in a common database, Apartment can help.
Uses schemas in Postgres, WEWT!
```
gem 'apartment'
```
[view on github](https://github.com/influitive/apartment) | [view on RubyGems](http://rubygems.org/gems/apartment) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/apartment)

**easier oauth functionality:**
```
gem 'open_auth2'
```
[view on github](https://github.com/sent-hil/open_auth2) | [view on RubyGems](http://rubygems.org/gems/open_auth2) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/open_auth2)

**A production ready Rails Engine that turns your app into an Oauth2 Provider:**
```
gem 'opro'
```
[view on github](https://github.com/opro/opro) | [view on RubyGems](http://rubygems.org/gems/opro) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/opro)

**Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions[https://github.com/archiloque/rest-client](https://github.com/archiloque/rest-client):**
```
gem 'rest-client'
```
[view on github](https://github.com/archiloque/rest-client) | [view on RubyGems](http://rubygems.org/gems/rest-client) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/rest-client)

**HMAC authentication client for Rails and ActiveResource:**
```
gem 'api-auth'
```
[view on github](https://github.com/mgomes/api_auth) | [view on RubyGems](http://rubygems.org/gems/api-auth) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/api-auth)

**Very simple Roles library without any authorization enforcement supporting scope on resource object. This library was intended to be used with CanCan and devise but should be generic enough to be used by any other authentication/authorization solutions:**
```
gem 'rolify'
```
[view on github](https://github.com/EppO/rolify) | [view on RubyGems](http://rubygems.org/gems/rolify) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/rolify)

**encryption:**
```
gem 'bcrypt-ruby', :require => 'bcrypt'
```

**Generates attr_accessors that encrypt and decrypt attributes:**
```
gem 'attr_encrypted'
```
[view on github](https://github.com/shuber/attr_encrypted) | [view on RubyGems](http://rubygems.org/gems/attr_encrypted) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/attr_encrypted)


## Javascript

**used for making searchable multiselect with tags and searching. Not a gem better for searching lots of records, it uses ajax calls find at [jquery-token](https://github.com/loopj/jquery-tokeninput). Put into vendor > assets > javascripts folder. Then load via asset pipline... see [Railscasts 258-token-fields-revised](http://railscasts.com/episodes/258-token-fields-revised) for example:**
```
gem 'chosen-rails'
```
[view on github](https://github.com/tsechingho/chosen-rails) | [view on RubyGems](http://rubygems.org/gems/chosen-rails) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/chosen-rails)

**add jquery autocomplete:**
```
gem 'rails3-jquery-autocomplete'
```
[view on github](https://github.com/crowdint/rails3-jquery-autocomplete) | [view on RubyGems](http://rubygems.org/gems/rails3-jquery-autocomplete) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/rails3-jquery-autocomplete)

**Rails gem for handling keyboard shortcuts via mousetrap javascript library:**
```
gem 'mousetrap-rails'
```
[view on github](https://github.com/kugaevsky/mousetrap-rails) | [view on RubyGems](http://rubygems.org/gems/mousetrap-rails) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/mousetrap-rails)

**ajaxify stuff - also add [jquery-pjax](https://github.com/defunkt/jquery-pjax):**
```
gem 'rack-pjax'
```
[view on github](https://github.com/eval/rack-pjax) | [view on RubyGems](http://rubygems.org/gems/rack-pjax) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/rack-pjax)

**Turbolinks makes following links in your web application faster. Instead of letting the browser recompile the JavaScript and CSS between each page change, it keeps the current page instance alive and replaces only the body and the title in the head. Think CGI vs persistent process:**
```
gem 'turbolinks'
```
[view on github](https://github.com/rails/turbolinks) | [view on RubyGems](http://rubygems.org/gems/turbolinks) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/turbolinks)

**Wiselinks makes following links and submitting some forms in your web application smarter and faster (this is really rad):**
```
gem 'wiselinks'
```
[view on github](https://github.com/igor-alexandrov/wiselinks) | [view on RubyGems](http://rubygems.org/gems/wiselinks) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/wiselinks)

**adds your ruby variables in your JS:**
```
gem 'gon'
```


## Image & File Manipulation

**used for imagemagick manipulations:**
```
gem 'rmagick'
```

**A ruby ImageMagick library that doesn't suck.(it is rad):**
```
gem 'image_sorcery'
```

**used for image uploads, eg avatars, etc - [a gentle introduction to carrierwave](http://www.engineyard.com/blog/2011/a-gentle-introduction-to-carrierwave/) :**
```
gem 'carrierwave'
```

**Process your uploads in the background by uploading directly to S3:**
```
gem 'carrierwave_direct'
```

**used for image uploads:**
```
gem 'paperclip'
```

**Automatic Retina Image Handling for Rails 3.1+:**
```
gem 'clear_eyes'
```


## System
**Generate Entity-Relationship Diagrams for Rails applications**
```
gem 'rails-erd'
```
[view on github](https://github.com/voormedia/rails-erd) | [view on RubyGems](https://rubygems.org/gems/rails-erd) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/rails-erd)

**An extensible open-source mobile backend framework**
```
gem 'helios'
```
[view on github](https://github.com/helios-framework/helios) | [view on RubyGems](http://rubygems.org/gems/helios) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/helios)

**A development tool that reveals your UI's bones**
```
gem 'xray-rails'
```
[view on github](https://github.com/brentd/xray-rails) | [view on RubyGems](http://rubygems.org/gems/xray-rails) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/xray-rails)

**Easy activity tracking for models - similar to Github's Public Activity**
```
gem 'public_activity'
```
[view on github](https://github.com/pokonski/public_activity) | [view on RubyGems](http://rubygems.org/gems/public_activity) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/public_activity)

**Security related headers all in one gem**
```
gem 'secure-headers'
```
[view on github](https://github.com/twitter/secureheaders)

**Send and retrieve your ruby i18n localizations to the Locale translation service**
```
gem 'localeapp'
```
[view on github](https://github.com/Locale/localeapp) | [view on RubyGems](http://rubygems.org/gems/localeapp) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/localeapp)

**Don't use 3rd party services to track your app errors. Use Github!**
```
gem 'party_foul'
```
[view on github](https://github.com/dockyard/party_foul) | [view on RubyGems](https://rubygems.org/gems/party_foul) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/party_foul)

**Inkwell adds social networking features – comments, reblogs, favorites, ability to follow other people and view their timeline**
```
gem 'inkwell', :git => 'git://github.com/salkar/inkwell.git'
```
[view on github](https://github.com/salkar/inkwell) | [view on RubyGems](https://rubygems.org/gems/inkwell) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/inkwell)

**Library for dealing with money and currency conversion**
```
gem 'money'
```

**Simple Rails app configuration**
```
gem 'figaro'
```

**Whitelist-based Ruby HTML sanitizer**
```
gem 'sanitize'
```

**Better error page for Rails and other Rack apps (for development only)**
```
gem 'better_errors'
```

**An attempt to tame Rails' default policy to log everything**
```
gem 'lograge'
```

**Engine Yard Local (Local Engine Yard Using VirtualBox)**
```
gem 'engineyard-local'
```

**Makes http fun again!:**
```
gem 'httparty'
```

**Every Rails page has footnotes that gives information about your application and links back to your editor:**
```
gem 'rails-footnotes'
```

**Nice profiling of application see [http://railscasts.com/episodes/368-miniprofiler](http://railscasts.com/episodes/368-miniprofiler) for more info:**
```
gem 'rack-mini-profiler'
```

**Seedbank allows you to structure your Rails seed data instead of having it all dumped into one large file. I find my seed data tended to fall into two categories. 1. Stuff that the entire application requires. 2. Stuff to populate my development and staging environments.:**
```
gem 'seedbank'
```

**Easily include static pages in your Rails app:**
```
gem 'high_voltage'
```
[view on github](https://github.com/thoughtbot/high_voltage) | [view on RubyGems](http://rubygems.org/gems/high_voltage) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/high_voltage)

**A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts:**
```
gem 'acts-as-taggable-on'
```

**A Rails plugin gem for filtering out profanity:**
```
gem 'profanity_filter'
```

**The ActiveRecord acts_as_commentable plugin:**
```
gem 'acts_as_commentable'
```

**Extension for Delayed Job to only run workers when needed on Heroku:**
```
gem 'workless'
```

**HireFire automatically "hires" and "fires" (aka "scales") Delayed Job and Resque workers on Heroku[http://hirefireapp.com/](http://hirefireapp.com/):**
```
gem 'hirefire'
```

**An ActiveModel validator that validates associated models, copying any errors from composed models up to their parent:**
```
gem 'also_validates'
```

**An IRB alternative and runtime developer console:**
```
gem 'pry'
```

**Connect to Pry remotely (for use with things like [POW](http://pow.cx)):**
```
gem 'pry-remote'
```

**A Ruby gem for communicating with the Twilio API and generating TwiML (SMS):**
```
gem 'twilio-ruby'
```

**handles events, like calling external apis etc:**
```
gem 'eventmachine'
```

**Doorkeeper is an OAuth 2 provider for Rails:**
```
gem 'doorkeeper'
```
**used for interacting with the cloud:**
```
gem 'fog'
```

**used for restful api creation:**
```
gem 'grape'
```

**General ruby templating with json, bson, xml, plist and msgpack support:**
```
gem 'rabl'
```

**used for backup:**
```
gem 'backup'
```

**A means of automating Heroku's pgbackups and archiving them to Amazon S3 via the fog gem**
```
gem 'pgbackups-archive'
```

**render custom json templates:**
```
gem 'jbuilder'
```

**The Exception Notifier plugin provides a mailer object and a default set of templates for sending email notifications when errors occur in a Rails application.:**
```
gem 'exception_notification'
```

**background job creation:**
```
gem 'resque'
```

**Love Resque? Hate Boilerplate? Use resque_def!:**
```
gem 'resque_def'
```
[view on github](https://github.com/schneems/resque_def) | [view on RubyGems](http://rubygems.org/gems/resque_def) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/resque_def)

**Sucker Punch is a Ruby asynchronous processing using Celluloid, heavily influenced by Sidekiq and girl_friday:**
```
gem 'sucker_punch'
```
[view on github](https://github.com/brandonhilkert/sucker_punch) | [view on RubyGems](http://rubygems.org/gems/sucker_punch) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/sucker_punch)


**[delayed job](https://github.com/collectiveidea/delayed_job):**
```
gem 'delayed_job_active_record'
```

**A Rails engine based frontend for Delayed Job. It also has an [iPhone app](http://itunes.apple.com/app/dj-mon/id552732872):**
```
gem 'dj_mon'
```

**A gem providing "time travel", "time freezing", and "time acceleration" capabilities, making it dead simple to test time-dependent code. It provides a unified method to mock Time.now, Date.today, and DateTime.now in a single call.:**
```
gem 'timecop'
```
[view on github](https://github.com/travisjeffery/timecop) | [view on RubyGems](http://rubygems.org/gems/timecop) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/timecop)

**runs multiple tasks at once for convenience:**
```
gem 'foreman'
```
[view on github](https://github.com/ddollar/foreman) | [view on RubyGems](http://rubygems.org/gems/foreman) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/foreman)

**Guard is a command line tool to easily handle events on file system modifications:**
```
gem 'guard'
```
[view on github](https://github.com/guard/guard) | [view on RubyGems](http://rubygems.org/gems/guard) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/guard)

**Do some browser detection with Ruby. Includes ActionController integration:**
```
gem 'browser'
```
[view on github](https://github.com/fnando/browser) | [view on RubyGems](http://rubygems.org/gems/browser) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/browser)

**used for scheduling things to run, like cron:**
```
gem 'whenever'
```

**Simple, efficient message processing for Ruby:**
Sidekiq uses threads to handle many messages at the same time in the same process. It integrates tightly with Rails 3 to make background message processing dead simple.
```
gem 'sidekiq'
```

**Chronic is a pure Ruby natural language date parser:**
```
gem 'chronic'
```

**Date and time formatting for humans:**
```
gem 'stamp'
```

**versioning:**
```
gem 'paper_trail'
```

**Track model actions:**
```
gem 'hound'
```
[view on github](https://github.com/injekt/hound) | [view on RubyGems](http://rubygems.org/gems/hound) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/hound)

**used for maintenance mode of sites:**
```
gem 'turnout'
```

**need to install redis on mac:**
```
gem 'redis'
```

**used for pretty urls:**
```
gem 'friendly_id'
```

**used for better design patterns see [Railscasts Draper](http://railscasts.com/episodes/286-draper) :**
```
gem 'draper'
```

**used for making a wizard eg installer:**
```
gem 'wicked'
```

**Simple Ruby wrapper for the GitHub v2 & v3 API:**
```
gem 'octokit'
```

**Helps you find your routes on a long Journey on Rails. Visit http://localhost:3000/rails/routes:**
```
gem 'sextant'
```

**The Active Record Reputation System helps you discover more about your application and make better decisions. The Reputation System gem makes it easy to integrate reputation systems into Rails applications, decouple the system from the main application and provide guidelines for good design of reputation systems:**
```
gem 'activerecord-reputation-system', :require => 'reputation_system'
```

**Keep model fields commented in your rails apps:**
```
gem 'annotator'
```

**New Relic RPM Agent:**
```
gem 'newrelic_rpm'
```

**Bullet: A rails plugin/gem to kill N+1 queries and unused eager loading**
```
gem 'bullet', :group => 'development'
```

**Search:**
```
gem 'ransack'
```

**Object-based searching (and more) for simply creating search forms:**
```
gem 'meta_search'
```


## Feature

**roll out particular features:**
```
gem 'rollout'
```

**A slick way to rollout features in your web app:**
```
gem 'rollout_ui'
```

**degrade features if failing or something like that:**
```
gem 'degrade'
```


## CMS

**mountable blog engine:**
```
gem 'monologue'
```

**refinery cms:**
```
gem 'refinerycms'
```

**Edit copy in your live web app (requires [copycopter-server](https://github.com/copycopter/copycopter-server):**
```
gem 'copycopter_client'
```
[view on github](https://github.com/cmeiklejohn/copycopter_client) | [view on RubyGems](http://rubygems.org/gems/copycopter_client) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/copycopter_client)

## Mail
**Incoming! helps you receive email in your Rack apps.**
```
gem 'incoming'
```
[view on github](https://github.com/honeybadger-io/incoming) | [view on RubyGems](http://rubygems.org/gems/incoming) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/incoming)

**A Rails engine that provides an endpoint for Sendgrid and sends the email to a specified class for processing**
```
gem 'griddler'
```
[view on github](https://github.com/thoughtbot/griddler) | [view on RubyGems](http://rubygems.org/gems/griddler) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/griddler)

**Forward mail from gmail IMAP to a callback URL, simply**
```
gem 'mail_room'
```
[view on github](https://github.com/tpitale/mail_room) | [view on RubyGems](http://rubygems.org/gems/mail_room) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/mail_room)

**Preview mail in the browser instead of sending**
```
gem 'letter_opener', :group => :development
```
[view on github](https://github.com/ryanb/letter_opener) | [view on RubyGems](http://rubygems.org/gems/letter_opener) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/letter_opener)

**used for viewing emails instead of sending tests:**
```
gem 'mail_view'
```

**Catches mail and serves it through a dream:**
```
gem 'mailcatcher'
```
Type **mailcatcher** to launch
Go to [http://localhost:1080/](http://localhost:1080/)
Send mail through **smtp://localhost:1025**

**auto inline styles for emails:**
```
gem 'roadie'
```

**An incoming mail processing microframework in Ruby: **
```
gem 'mailman'
```

**Write your ActionMailer email templates in Markdown, send in html and plain text**
```
gem 'maildown'
```
[view on github](https://github.com/schneems/maildown) | [view on RubyGems](http://rubygems.org/gems/maildown) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/maildown)


## WYSIWYG
**The redactor-rails gem integrates the Redactor editor with the Rails 3.2 asset pipeline.**
```
gem 'redactor-rails'
```
[view on github](https://github.com/SammyLin/redactor-rails) | [view on RubyGems](http://rubygems.org/gems/redactor-rails) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/redactor-rails)


**asset pipeline based ckeditor:**
```
gem 'ckeditor_rails', :require => 'ckeditor-rails'
```

**ckeditor:**
```
gem 'ckeditor', '3.7.1'
```

**used for WYSIWYG editor:**
```
gem 'tiny_mce'
```


## Visual
**Rails generator to build a styleguide**
```
gem 'styleguide_rails'
```
[view on github](https://github.com/begriffs/styleguide_rails) | [view on RubyGems](http://rubygems.org/gems/styleguide_rails) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/styleguide_rails)

**Entity-style text parsing extracted from Cheddar**
```
gem 'quesadilla'
```
[view on github](https://github.com/soffes/quesadilla) | [view on RubyGems](http://rubygems.org/gems/quesadilla) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/gems/quesadilla)

**Garlic.js in love with Rails Asset Pipeline(saves forms):**
```
gem 'garlicjs-rails'
```

**Speeds up your Rails 3 assets:precompile by only recompiling changed files, and only compiling once to generate all assets:**
```
gem 'turbo-sprockets-rails3'
```

**admin interface:**
```
gem 'activeadmin'
```

**admin interface:**
```
gem 'rails_admin', :git => 'git://github.com/sferik/rails_admin.git'
```

**adds auto haml support:**
```
gem 'haml-rails'
```

**adds better form stuff:**
```
gem 'simple_form'
```

**Easy dynamic nested fields for Rails and jQuery applications:**
```
gem 'awesome_nested_fields'
```

[view on github](https://github.com/lailsonbm/awesome_nested_fields) | [view on RubyGems](http://rubygems.org/gems/awesome_nested_fields) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/awesome_nested_fields)

**Synchronises Assets between Rails and S3:**
```
gem 'asset_sync', :group => :assets
```

```
gem 'zurb-foundation', :group => :assets # great starter for layouts
```
```
gem 'twitter-bootstrap-rails', :git => 'http://github.com/seyhunak/twitter-bootstrap-rails.git'
```

**yet another sass based twitter bootstrap:**
```
gem 'bootstrap-sass'
```

**[sass-twitter-bootstrap](https://github.com/jlong/sass-twitter-bootstrap):**
```
gem 'sass-twitter-bootstrap'
```

**cool semantic forms:**
```
gem 'formtastic'
```

**ClientSideValidations for Ruby on Rails:**
```
gem 'client_side_validations'
```

**used for pdf generation:**
```
gem 'prawn'
```

**used for pdf generation:**
```
gem 'wicked_pdf'
```

**json printing which is very pretty:**
```
gem 'awesome_print'
```

**A simple, pure Ruby implementation of JSON code coloring:**
```
gem 'pizzazz'
```

**Provides a simple helper to get an HTML select list of countries. The list of countries comes from the ISO 3166 standard. While it is a relatively neutral source of country names, it may still offend some users:**
```
gem 'country-select'
```

**Logic-less Ruby templates**
```
gem 'mustache'
```

**Rails gem for handling keyboard shortcuts via mousetrap javascript library:**
```
gem 'mousetrap-rails'
```

## Pagination

**hardcore pagination:**
```
gem 'kaminari'
```

**general pagination:**
```
gem 'will_paginate'
```

**bootstrap general pagination:**
```
gem 'bootstrap-will_paginate'
```

**BreadcrumbsOnRails is a simple Ruby on Rails plugin for creating and managing a breadcrumb navigation for a Rails project. It provides helpers for creating navigation elements with a flexible interface:**
```
gem 'breadcrumbs_on_rails'
```


## eCommerce

**online store:**
```
gem 'spree'
```

**If you get an “Unable to resolve dependencies” error while installing the Spree gem you can try installing just the spree_cmd gem instead (which has minimal dependencies.):**
```
gem 'spree_cmd'
```

**stripe payment method for spree commerce:**
```
gem 'spree_stripe'
```
[view on github](https://github.com/adiastyle/spree-stripe)

**used for billing etc:**
```
gem 'activemerchant', :require => 'active_merchant'
```

**Stripe webhook integration for Rails applications.:**
```
gem 'stripe_event'
```
[view on github](https://github.com/integrallis/stripe_event) | [view on RubyGems](http://rubygems.org/gems/stripe_event) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/stripe_event)

**Stripe Ruby bindings:**
```
gem 'stripe'
```
[view on github](https://github.com/stripe/stripe-ruby) | [view on RubyGems](http://rubygems.org/gems/stripe) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/stripe)

**Recurring Billing: A Chargify API wrapper for Ruby using ActiveResource.:**
```
gem 'chargify_api_ares'
```


## Servers
**super fast concurrent web server:**
```
gem 'puma'
```

**A very fast & simple Ruby web server:**
```
gem 'thin'
```

**Phusion Passenger (mod_rails):**
```
gem 'passenger'
```


## Other that I have no place for yet

**XML, HTML PARSING ETC:**
```
gem 'nokogiri'
```

**geo mapping [geokit-gem](https://github.com/imajes/geokit-gem), also use the plugin [geokit-rails](https://github.com/imajes/geokit-rails) for advanced functionality:**
```
gem 'geokit'
```

**Squeel lets you write your ActiveRecord queries with fewer strings, and more Ruby, by making the ARel awesomeness that lies beneath ActiveRecord more accessible.:**
```
gem 'squeel'
```


## Development

**Code coverage for Ruby 1.9 with a powerful configuration library and automatic merging of coverage across test suites:**
```
gem 'simplecov', :require => false, :group => :test
```

**Flog reports the most tortured code in an easy to read pain report. The higher the score, the more pain the code is in.:**
```
gem 'flog'
```

[view on github](https://github.com/seattlerb/flog) | [view on RubyGems](http://rubygems.org/gems/flog) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/flog)

**Flay analyzes code for structural similarities. Differences in literal values, variable, class, method names, whitespace, programming style, braces vs do/end, etc are all ignored. Making this totally rad.:**
```
gem 'flay'
```

[view on github](https://github.com/seattlerb/flay) | [view on RubyGems](http://rubygems.org/gems/flay) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/flay)

**Collection of testing matchers extracted from Shoulda.:**
```
gem 'shoulda-matchers'
```

[view on github](https://github.com/thoughtbot/shoulda-matchers) | [view on RubyGems](http://rubygems.org/gems/shoulda-matchers) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/shoulda-matchers)

**A tool for detecting missing unique indexes in Rails projects.:**
```
gem 'consistency_fail'
```

[view on github](https://github.com/trptcolin/consistency_fail) | [view on RubyGems](http://rubygems.org/gems/consistency_fail) | [view on The Ruby Toolbox](https://www.ruby-toolbox.com/projects/consistency_fail)

*group :test*
```
gem 'cucumber-rails'
```
```
gem 'database_cleaner'
```

*group :test, :development*
```
gem launchy'
gem 'nokogiri'
```

**used for creating api docs from rspec:**
```
gem 'rspec_api_documentation'
```

**Helpful rake tasks for Heroku:**
```
gem 'heroku_san'
```

```
gem 'capistrano'
```

**Battle-tested capistrano recipes for ruby, rubygems, apache, passenger, delayed_job, juggernaut, thinking_sphinx, mongodb, whenever, among other popular tools:**
```
gem 'cap-recipes'
```

**Really fast deployer and server automation tool(Optional and maybe better than capistrano?)**
```
gem 'mina'
```

```
gem 'rspec-rails'
```

```
gem 'email_spec'
```

```
gem 'capybara'
```

**Test your ActionMailer and Mailer messages with Capybara**

```
gem 'capybara-email'
```

```
gem 'capybara-screenshot', :group => :test
```

```
gem 'guard-rspec'
```

```
gem 'growl_notify'
```

```
gem 'cucumber'
```

```
gem 'brakeman'
```

```
gem 'annotate'
```

```
gem 'nifty-generators'
```

```
gem 'factory_girl_rails'
```

**Generate fake data for your tests**
```
gem 'faker`
```

**Used for rails Panel**
```
gem 'meta_request'
```

**used for checking your code:**
```
gem 'rails_best_practices'
```
