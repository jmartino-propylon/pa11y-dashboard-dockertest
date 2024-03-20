# Test Docker Container for pa11y-dashboard

## How to run
* clone this repo
* docker compose build
* docker compose up
* open your browser to localhost:4000

## What's behind the curtains?
Two containers:
One for latest node:slim
Other for MongoDB

Everytime we build the image; it will pull latest updates for the node:slim image; install latest chrome stable and latest version of pa11y-dashboard
Once the build is done; then the compose up will run the containers. That's it.