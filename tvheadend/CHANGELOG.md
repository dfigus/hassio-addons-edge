# Changelog since v4.1.4
- Merge pull request #61 from dfigus/use-media-folder-for-recording 
- Switch recordings folder to media 
- Merge pull request #60 from dfigus/remove-build-latest-tvheadend-commit

Remove fallback to build latest TVHeadend commit 
- Remove fallback to build latest TVHeadend commit
Remove the fallback logic that would build the latest TVHeadend commit
in case the ARG is not set - which should never occur, as we pin to a
specific commit in the Dockerfile. TVHeadend commits are bumped via
Renovate Bot. 
- Merge pull request #59 from dfigus/set-stage-stable 
- Remove stage experimental 
