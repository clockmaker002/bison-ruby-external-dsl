require 'rspec'
require 'rspec/rake/spectask'

task :default => :rspec

desc "Running specs."
Spec::Rake::SpecTask.new(:spec) do |t|
  t.spec_files = FileList['spec/**/*_spec.rb']
  t.spec_opts = ['--options', 'spec/spec.opts']
end
