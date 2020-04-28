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

namespace :db do


  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end
