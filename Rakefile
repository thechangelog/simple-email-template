require 'rubygems'
require 'bundler'
Bundler.setup

desc "Run middleman server"
task :server do
  puts "*** Middleman server go! ***"
  system 'bundle exec middleman server'
end

desc "Run middleman build"
task :build do
  puts "*** Middleman build! ***"
  system 'bundle exec middleman build'
end

desc "Clear the build"
task :clear do
  puts "*** Clearing the build! ***"
  system 'rm -Rfv build'
end

desc "Zip the build"
task :zip do
  puts "*** Zipping the build! ***"
  system 'rm -Rf build.zip'
  system 'zip -r build.zip build/*'
end
