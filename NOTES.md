## What is ActiveRecord?
(see if students can answer)

 -Activerecord is a gem that is an ORM

## What is Rake?
in terminal: rake -T

## create migration
rake db:create_migration NAME=migration_name

def change
    create_table :table_name do |t|
        t.string /attributes
    end
end


## create model in lib folder
class table_name < ActiveRecord::Base


## use rake.console 
show how you can create a new instance of the class, then use save method
then call ModelName.methods to show all the methods available. 

## show difference between .new and .create


## go over plural vs singular and has_many and belongs to associations. 
