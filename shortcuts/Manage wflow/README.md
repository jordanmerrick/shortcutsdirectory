# Manage.wflow
    
Submitted by: [@melangue](https://github.com/melangue)

Manage.wflow is a backup tool unlike most others.  
It does not zip up workflows but copys them to iCloud in a created path and let's you restore them.

[Get workflow](workflow://import-workflow/?url=https://github.com/jordanmerrick/workflowdirectory/raw/master/workflows/Manage%2520wflow/Manage.wflow)

**Full disclosure:**  
This workflow was created by [/u/bigdeeb](https://www.reddit.com/user/bigdeeb) and I found it on [reddit](https://www.reddit.com/r/workflow/comments/64ev7a/managewflow/).  
It was quite extensively modified by me and there a lot of new features.  
I find it really useful for keeping my list of workflows clean.

## Features
### Restore Workflow
Restore workflows from your iCloud Drive.  
Choose a folder from a list, filter the results and choose a workflow to restore.  
It will clean up the names (added when Auto-Archiving) of each workflow restored.

### Restore Workflow by Name
Let's you type in a partial name of the workflow and after some calculations it will present a list of workflows with matching names to be restored.  
This one also cleans up the name of restored workflow.

### Auto-Archive Workflows
It uses categories for archiving & restoring workflows, present as dictionaries.  
This allows it to do some auto-archiving based on workflow names.

It works like this:  
Prior to using the Manage.wflow you need add a certain keyword to each workflow's name, let's say we add  ` DL` to a couple of downloader type workflows.  
Choose `Auto-Archive Workflows` from Manage.wflow menu and it will present you a list of categories.  
Pick ` DL` and it will grab all of the workflows containing that category's keyword and archive them to that category's folder - `DL/`.

There are currently 4 categories present - ARC, UTIL, DL, FUN and all of them work the same way.

### Backup All Workflows
Nothing fancy here, grabs all of your workflows, puts them in an archive and saves them to `Manage.wflow/backup/` folder with today's date it's name.

### View Workflow XML Contents
As advertised

### Display Workflow Binary Contents
As advertised
