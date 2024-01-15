# Changelog since v4.1.4
- Merge pull request #64 from dfigus/nginx-allow-only-from-haos

NGINX security enhancements 
- NGINX Listen on default ingress port 8099 
- NGINX accept only connections from haos
Only allow inbound NGINX connections from the HAOS ingress ip
172.30.32.2 and disable listening on IPv6. 
- Merge pull request #63 from dfigus/picons-regex-versioning

Define regex versioning for picons releases 
- Define regex versioning for picons releases 
- Merge pull request #62 from dfigus/renovate/picons-picons-2024.x

⬆️ Update picons/picons to v2024-01-11--21-19-56 
- ⬆️ Update picons/picons to v2024-01-11--21-19-56 
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
