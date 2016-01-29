# Asana Create Task

This [Dexter](http://rundexter.com) module will create a new Asana task.

# Configuring the Step

## Input parameters

Parameter|Required|Multiple?|Details
---------|--------|---------|-------
Assignee | No | No | The person to whom the task is assigned
Notes | No | No | The task description
Followers | No | No | Emails of users that will follow the task 
Name | No | No | The name of the task
Workspace | Yes | No | The Asana Workspace ID

# Getting Asana credentials

To use this module, you'll have to create an app and authenticate yourself with it.

1. Log into your Asana account
1. Navigate to the "My Profile Settings" section
1. Go to Apps
1. Click "+ Add New Application"
1. Fill in the required fields. For the required URLs, please use "http://rundexter.com"

You should now have the following:
* **Client ID**
* **Client Secret**

Add those into the OAuth configuration panel. Save and test. That's it!
