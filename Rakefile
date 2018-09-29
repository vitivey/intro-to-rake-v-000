namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  task :hola do
    prints "hola de Rake!"
  end
end

namespace :db do
  task :migrate => :environment do

  end

  task :seed do
    require "./db/seeds.rb"
  end
end
