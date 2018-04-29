# Podcast
This repo contains all data/files for the podcast itself.

## Uploading
- Please follow the filename convention used throughout the repo
- File names should look like this: ```SystemdotDebugLevel###.mp3```
- Add description and other pertinent information to the JSON file

## Merging
Upon merging, a circleci job will be kicked off which will then generate the appropriate files and call the appropriate services in order to get the uploaded episodes live.
