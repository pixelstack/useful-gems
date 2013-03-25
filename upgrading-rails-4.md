#Upgrading Rails: Gems Extracted in Rails 4
As from http://alindeman.github.com/2013/03/05/gems-extracted-in-rails-4.html

During the development of Rails 4, many features that were present in earlier versions of Rails were removed from Rails itself and extracted to gems.

Extracting features to gems slims down Rails itself, and allows Rails to take a different direction to solve certain problems. For example, [strong_parameters](https://github.com/rails/strong_paramters) in Rails 4 is recommended over attr_accessible and attr_protected from Rails 3 when an application needs to protect itself from mass-assignment vulnerabilities.

Furthermore, some of the extracted gems have new maintainers. These fresh maintainers might respond more quickly to bug and feature requests than the Rails core team feasibly can.

Unfortunately, existing applications that are upgraded to Rails 4 may need to pull in several new gems in order to perform properly. I have compiled a list of these extracted gems and the features they provide. If your application uses any of the listed features, you'll want to pull them into Gemfile while upgrading to Rails 4.

[protected_attributes](https://github.com/rails/protected_attributes)  
Because Rails 4 recommends strong_parameters for mass-assignment protection, attr_accessible and attr_protected have been extracted. I expect that most upgraded applications will need this gem, as the transition to strong_parameters can be tedious and error-prone.

[activeresource](https://github.com/rails/activeresource)  
While the ActiveRecord-like abstraction over a RESTful API has always shipped as a gem, it is no longer included with Rails by default. Include it explicitly if your application requires it.

[actionpack-action_caching](https://github.com/rails/actionpack-action_caching)  
[actionpack-page_caching](https://github.com/rails/actionpack-page_caching)  
Rails 4 includes many improvements to fragment caching, but action and page caching have been extracted. If your application uses action or page caching, be sure to pull these gems in explicitly.

[activerecord-session_store](https://github.com/rails/activerecord-session_store)  
The ability to store session data in a database table has been extracted in Rails 4. If your application uses the ActiveRecord session store, include this gem.

[rails-observers](https://github.com/rails/rails-observers)  
Rails no longer encourages the use of observers, separate objects that can react to lifecycle events of ActiveRecord models. If your application uses observers, make sure to include this gem.

[actionpack-xml_parser](https://github.com/rails/actionpack-xml_parser)  
Following security vulnerabilities involving inbound XML, Rails extracts the ability to accept XML input to a gem. If your application accepts XML in a request body (note: this is distinct from responding with XML), you will need to pull in this gem.

[rails-perftest](https://github.com/rails/rails-perftest)  
Rails 4 extracts ActionDispatch::PerformanceTest. If your application includes performance tests (usually located in test/performance), add this gem to your bundle.

[actionview-encoded_mail_to](https://github.com/reed/actionview-encoded_mail_to)  
Rails previously included a little-known feature to obfuscate email addresses in hyperlinks, either with HTML entities or JavaScript code. If your application uses the encode option with mail_to, include this gem.
