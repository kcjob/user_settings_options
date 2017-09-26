# user_settings_options
Part 2 of email reminder project

As with most project, there is never one thing.  In this case if you send someone a reminder email, you need to give them the option of opting out.  
This application has been broadened to allow for access to the settings column of the core user table in the database.  The value in settings is a json string.  The json string holds various options the affects the user's iteraction with the database
For example, whether a user has optedout of receiving reminder emails.
