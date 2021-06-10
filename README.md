# Wildlife Tracker Challenge


$ rails new myapp -d postgresql -T
$ cd myapp
$ rails db:create
$ bundle add rspec-rails
$ rails generate rspec:install
$ rails server


Student
name:string
cohort:string

rails g resource Student name:string cohort:string


Add this to be able to create:
class ApplicationController < ActionController::Base
  skip_before_action :verify_authenticity_token
end
