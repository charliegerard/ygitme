require "bundler/gem_tasks"
require 'rake/testtask'

task :default => :test do
end

Rake::TestTask.new do |t|
	  t.libs << "test"
		  t.test_files = FileList['test/test*.rb']
			  t.verbose = true
end
