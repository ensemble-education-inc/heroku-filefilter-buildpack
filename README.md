# Heroku Buildpack: File Filter

This buildpack has a purpose of filtering out all the files of a given extension from the build repo. Its intention was to be used for a monorepo which has a lot of images, so the png files will be removed and not deployed to the Heroku backend.

# Usage

To use this buildpack, add it to your build process and define a config var called `FILTER_EXTENSION`. The
value here is a single extension or a comma-separated list of extensions to be deleted.
