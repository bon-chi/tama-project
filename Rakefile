task :default => [:spec]
begin
  require 'rspec/core/rake_task'
  RSpec::Core::RakeTask.new(:spec) do |spec|
    spec.pattern = 'spec/**/*_spec.rb'
    # spec.rspec_opts = ['-cfs']
  end
rescue LoadError => e
end
# # Add your own tasks in files placed in lib/tasks ending in .rake,
# # for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.
#
require File.expand_path('../config/application', __FILE__)
# # require "rspec/core/rake_task"
# # Rspec::Core::RakeTask.new("spec")
# # task :default => :spec
Rails.application.load_tasks
