namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db do
  task :environment do
    require "./config/environment.rb"
  end
  task :migrate => :environment do
    Student.create_table
  end

  task :seed do
    require "./db/seeds.rb"
  end
end
