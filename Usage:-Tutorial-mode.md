In tutorial mode (--action=tutorial) the job is doing the following actions:

* gather custom options from the user (see Init mode)
* generating options.json if none in rot folder
* generating _Sidebar.md
* removing the options.json file at the end
* if --git-push is set, it tries to push the changes to origin repository