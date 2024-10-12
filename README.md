# Heroku Buildpack: File Filter

This buildpack has a purpose of filtering out all the files of a given extension from the build repo. Its intention was to be used for a monorepo which has a lot of images, so the png files will be removed and not deployed to the Heroku backend.
