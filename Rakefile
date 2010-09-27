begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "rkj-merb-i18n"
    gemspec.summary = gemspec.description = "Merb plugin that provides bindings to r18n"
    gemspec.email = "roman.kamyk@itiner.pl"
    gemspec.homepage = "http://github.com/rkj/merb-i18n"
    gemspec.authors = ['Andrey "A.I." Sitnik', "Tymon Tobolski"]
    gemspec.add_dependency('merb-core', '>= 1.0')
    gemspec.add_dependency('r18n-core', '~> 0.4.8')
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

desc "Run specs"
task :spec do
  system("spec -O spec/spec.opts spec")
end
