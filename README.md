# python_login_app
Python powered web login application using MongoDB

This application is a slow work in progress.  It is an adaptation of a NodeJS program I wrote ages ago, but I hope to make it more stable than the NodeJS version. It is set up to run on one server/system.

CURRENT STATUS:   0% COMPLETE

Program summary:
  This program will track visitors who are granted entry to desired locations. The display will show the fields for a vistor log into the location (system).  The generated user tiles can be clicked, allowing the visitor to edit their entered data (not timestamps), as well as logging out of the application.  

  The associates are allowed to download reports per month, yearly reports (up to 2 years), as well as full database reports.  Associates are also allowed to edit user data for up to a month. After that, the superuser will have to edit the database directly.

App uses:
- Login page to gain access to the app
- Security will not be tight as it is designed to work inside the local network
- Pages:
    > Data entry page & showing currently logged in users (current setup is for people visiting a location)
    > Visitor edit page, designed for visitors to edit any data which was entered incorrectly
    > Associate edit page, Allows associates who have access to edit data on a user (database edits)
    > Reports page. A self-generating page which displays reports for every month (auto labels and sorts them) for up to 2 years
    > Page for easy associate viewing/edits. This does not allow new entries, only the editing of currently logged in visitors, and logging them out
        if required.
- Automatically removes reports, error logs, etc, preventing system bloat due to logs not being managed correctly.
