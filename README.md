# ArkBackupServer Support and Downloads

This repository is used to:
- Track bugs and feature requests through GitHub Issues
- Provide the latest version of the app as a downloadable executable

This is simple to use with the following

Usage: ArkBackupServer {ftp-url} {username} {password} {remote-path} {local-path}

This will then create a copy of that Map into the local-path and then create a Zip backup of these files.

The first run will take arond 30mins, then each subsequent run will be around 1 or 2 min as it will only download changes.


