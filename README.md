Get Things Done
===============
Context specific reminders

When you think of something you need to get done, but aren't in a position to do it immediately, record the task and the minimum/ideal conditions for doing it. When the conditions are met, you will be reminded.

Contexts
--------
 - Location
 - Open application
 - Date & Time
 - Dependencies

Examples
--------
Call Matt about such and such after curret task is complete but no later than 25 minutes from now.
```
Call Matt about such and such
@depends #current-task complete
@nolaterthan 25m
```
Buy toilet paper when near a Wallmart but no later than 2 days from now
```
Buy toilet paper
@near Wallmart
@nolaterthan 2d
```
Fix abc.com landing page defect LP-349 next time I have that project open
```
Fix landing page defect LP-349
@open [text-editor] abc.com
@nolaterthan 1w
```
