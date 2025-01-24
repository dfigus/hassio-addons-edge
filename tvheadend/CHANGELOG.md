# Changelog since v7.0.1
- Merge pull request #332 from dfigus/fix-duplicate-wg++-build

Remove Duplicate WG++ Build in Dockerfile 
- Remove Duplicate WG++ Build in Dockerfile 
- Merge pull request #331 from dfigus/fix-race-condition-config-folder-creation

Fix Race Condition in Config Folder Creation 
- Fix Race Condition in Config Folder Creation
Make sure that only init-tvheadend is creating the config folder and
that it is started before other services that depend on it. Otherwise
the --firstrun of TVHeadend might not be called at all. 
