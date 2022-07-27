# moodle-lifecycletrigger_inactivetime
This is a trigger-Subplugin for the admin tool [moodle-tool_lifecycle](https://github.com/learnweb/moodle-tool_lifecycle). 
Course without log data within the given timeperiod are marked for the cleanupprocess of the lifecycle admin tool.

## Settings
Site administrators choose the period of time in which no log data for the course must be available, to get the course marked for the cleanupprocess. 

## Proceeding
A trigger plugin always receives one course. To determine whether the course should be deleted the plugin 
checks if there are any log entries for the course wihtin the given period. If no log data was found, the course will be marked for the cleanupprocess.
  
 For detailed information on trigger plugins visit the 
[Wiki](https://github.com/learnweb/moodle-tool_lifecycle/wiki) of the lifecycle admin tool.
