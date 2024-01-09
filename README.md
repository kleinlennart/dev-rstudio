# dev-rstudio

## Notes
- is `/workspaces/dev-rstudio` also the directory for my .Rproj?
- or can i have multiple .Rproj s?
- that is not really the idea, though
- build a baseline setup here that I can replicate for every other repo to make them reproducible 


## Ideas
- hard code R version
  -  add "image": "ghcr.io/rocker-org/devcontainer/r-ver:4",
- set installed packages (pak, tidyverse, etc.)
- install Quarto? (make optional, because longer run time)

apt-packages
r-packages


- initial_working_directory

This Feature sets onCreateCommand to the Docker image, and the onCreateCommand sets initial_working_directory to the rstudio-prefs.json file (A file containing RStudio preferences) immediately after container creation.

