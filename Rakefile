desc "Run lib/frac_main.rb"
task :bin do
  sh "ruby -Ilib lib/frac_main.rb"
end

desc "Run tests with --format documentation"
task :test do
  sh "rspec -Ilib test/racional_spec.rb --format documentation"
end

desc "Run tests with format: html"
task :thtml do
  sh "rspec test/racional_spec.rb --format html"
end

