! Project Management App 

# With Ruby on Rails

### What are we building? Projekt

The goal of the application is to be a home for any amount of projects. A project lives within a team and can have as many users as necessary. A user can only belong to one team at a time . Ultimately, we'd want to extend this to allow a single user to belong to multiple teams.

The app will have 3 overlying models/relationships to tie together :

1. A User can create a project if they belong to a team.
2. Creating a team assigns both your own account plus those you invite to a team.
3. Projects require a team in order to be created.
