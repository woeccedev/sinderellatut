require "bundler/gem_tasks"
require 'rspec/core/rake_task'
require 'bundler/gem_tasks'

# Default directory to look in is '/specs'
# Run with 'rake spec'
RSpec::Core::RakeTask.new(:spec) do |task|
	task.rpsec_opts = ['--color', '--format', 'nested']
end

task :default => :spec