source ENV['GEM_SOURCE'] || "https://rubygems.org"

group :unit_tests do
  gem 'rake',                                                       :require => false
  gem 'rspec', '~> 3.1.0',                                          :require => false
  gem 'rspec-puppet',                                               :require => false
  gem 'puppetlabs_spec_helper',                                     :require => false
  gem 'puppet-lint', '1.0.1',                                       :require => false
  gem 'puppet-syntax',                                              :require => false
  gem 'metadata-json-lint',                                         :require => false
  gem 'json',                                                       :require => false
  gem 'puppet-lint-absolute_classname-check',                       :require => false
  gem 'puppet-lint-appends-check',                                  :require => false
  gem 'puppet-lint-empty_string-check',                             :require => false
  gem 'puppet-lint-file_ensure-check',                              :require => false
  gem 'puppet-lint-leading_zero-check',                             :require => false
  gem 'puppet-lint-spaceship_operator_without_tag-check',           :require => false
  gem 'puppet-lint-trailing_comma-check',                           :require => false
  gem 'puppet-lint-undef_in_function-check',                        :require => false
  gem 'puppet-lint-unquoted_string-check',                          :require => false
  gem 'puppet-lint-version_comparison-check',                       :require => false
  gem 'puppet-lint-classes_and_types_beginning_with_digits-check',  :require => false
  gem 'puppet-lint-trailing_newline-check',                         :require => false
  gem 'puppet-lint-variable_contains_upcase',                       :require => false
  gem 'puppet-lint-strict_indent-check',                            :require => false
end
group :development do
  gem 'simplecov',   :require => false
  gem 'guard-rake',  :require => false
end
group :system_tests do
  gem 'vagrant-wrapper',  :require => false
  gem 'beaker-rspec',     :require => false
  gem 'serverspec',       :require => false
end

if facterversion = ENV['FACTER_GEM_VERSION']
  gem 'facter', facterversion, :require => false
else
  gem 'facter', :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

