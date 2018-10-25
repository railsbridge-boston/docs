getting up and running:
* sign up for a free codenvy account. create a new workspace. Under stack, pick "Rails". Leave all other settings at their default and click "Create".
* Once the workspace is up, go to workspace->new project. click "blank", enter a name "sugg" then click "Create"
* then in the terminal, from the projects folder type "rails new sugg" which will make the rails app in the project folder made in the previous step
* you can now run the project from the top menu, which cds into the "sugg" project and correctly runs "rails server -b 0.0.0.0"

notes on usage:
* loads up rails 5.0.7 right now, which i think is fine (no material difference between 5.0 and 5.2 in hte curriculum i think)
* need to add "gem 'rb-readline'" to gemfile to get rails console to work
* it doesnt seem possible to open a file from the terminal. must use the file browser
* copy/paste and such seems to work well (ctrl+v ctrl+c on windows)
* it was a bit more finicky when inside the rails console, but still worked if i made sure the terminal had focus

workspace:
* workspaces go to sleep after 10 minutes of inactivity. must click "resume", this takes about 2minutes or so for it to spin back up. annoying but not totally a dealbreaker
