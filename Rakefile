require 'rake'
require 'rake/testtask'
require 'rake/rdoctask'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    root_files = FileList["README.md", "COPYING", "init.rb"]
    s.name = "puavo-view-helpers"
    s.summary = "View helpers for Puavo applications"
    s.email = "puavo@opinsys.fi"
    s.homepage = "https://github.com/jpkorhonen/puavo-view-helpers"
    s.description = "View helpers for Puavo applications"
    s.authors = "Jouni Korhonen"
    s.files =  root_files + FileList["{rails,lib}/**/*"]
    s.extra_rdoc_files = root_files
  end

  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: gem install jeweler"
end
