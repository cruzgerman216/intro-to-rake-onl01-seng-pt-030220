desc 'outputs hello to the terminal'
namespace :greeting do
  task :hello do
    puts "hello from Rake!"
  end
  task :hola do
    puts "hola de Rake!"
  end
end

namespace :Rake do

  desc 'drop into the Pry console'
Task :console => :environment do
  Pry.start
end
end
