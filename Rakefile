require "./app"
Dir.glob('lib/tasks/*.rake').each { |r| load r}

begin
  require 'rspec/core/rake_task'
  RSpec::Core::RakeTask.new(:spec)
rescue LoadError
end

