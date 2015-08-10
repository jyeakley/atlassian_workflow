# atlassian_workflow
Alfred Atlassian Workflow

##Description
This workflow was created to integrate alfred with the Atlassian tool suite. Currently, this workflow only supports JIRA integration.

##Usage

###Setup Information
Before you can use this workflow, you must setup the basic connection information using the "atlassianinfo" keyword. From here you have the following options:

  1. Set the hostname (required): This is the hostname that your Atlassian server lives.
  2. Set the username (required): Sets your username for Atlassian.
  3. Set the password (required): Sets you password for Atlassian login.

###JIRA Keywords
After your information has been set, you can use these useful keywords:

  1. jirasetfilter - This keywords fetches all your current saved filters and allows you to select one to set as the "current filter".
  2. jirafilter - This keyword fetches all current issues based on the current set filter (selecting will open in default browser).
  3. jiraassign <username> - This keyword followed by a valid username, will fetch all issues based on the current set filter (selecting will assign the issue to the username input).
  4. jiracomment <comment> - This keyword followed by a comment, will fetch all issues based on the current set filter (selecting will add the input as a comment to the issue).
  5. jirawork <timespent> (not funtional yet) - This keyword followed by timespent (ex. 1d 5h), will fetch all issues based on the current set filter (selecting will add the input as a timespent to the issue).
  6. jiraowner <username> - This keyword followed by a valid username, will fetch all issues based on the input username.
  7. jirasearchdesc <description text> - This keyword followed by some description text, will fetch all issues that have matching summary text based on input.
  8. jirasearchid <issue id> - This keyword followed by some issue id, will fetch all issues that have matching issue id on input.
