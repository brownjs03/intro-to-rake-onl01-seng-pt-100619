namespace :greeting do 
desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc 'outputs confirmation to the terminal'
task :confirm do 
  puts "Yep, this works!"
end 
end 

namespace :db do 
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    student.create_table
  end 
end 

task :environment do
  require_relative './config/environment'
end 