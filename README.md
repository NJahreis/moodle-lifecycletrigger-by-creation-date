# Moodle Lifecycletrigger By Creation Date

Trigger-Subplugin for moodle-tool_lifecycle. It checks how long ago the course was created (mdl_course.timecreated DB field). If so, it marks the course for the cleanup process. Directly based on the core start date delay trigger by Tobias Reischmann.

## Settings

Delay sets the delay since the creation time of the course before it is triggered by the workflow.