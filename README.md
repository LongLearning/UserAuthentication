#Basic reusable User Authentication

##Goals:
* Learn to use Rails 3
* Look into Postgres
* Create a User model
* Basic RSpec testing
* Authenticate user with device
* Create Roles
* Use CanCan for Authorization

###Workflow
1. Choose an issue you want to work on. (I'll try to create them in logical order)
2. Create a local branch (issueNumber_descriptiveName)
3. Make your changes
4. Push to origin/your_local_branch_name
5. Create on GitHub a pull request
6. Wait for my code review and make needed changes (you can start on a new issue on a different branch, if you don't need the new code to do so)
7. Merge it in GitHub.

###To reuse this
1. Clone the new project repository or create a project directory locally
2. Copy the code inside UserAuthentication into your new project.
3. Change everywhere the name UserAuthentication to your projects name.
4. Change the config/database.yml to use different databases 
5. Change the Readme (if you clone, use the existing one) 
6. Create a new project related rvm gemset and change the .rvmrc file
7. Adjust the Gemfile to the needs of your new project
8. Run `bundle install` and `rake db:create`
9. Start your server and check the page
(I think this works like this, but the Readme should be changed if not)