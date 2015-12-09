Heroku buildpack: Python, Numpy, and Scipy (Python 2.7 only)
====================================================


This custom buildpack based on [thenovice's] (https://github.com/thenovices/heroku-buildpack-scipy).  Buildpacks
allow for customization and greater control of the Heroku setup process. (you can read more about it [here] 
(https://devcenter.heroku.com/articles/buildpacks)).  The purpose of hosting our own buildpack is to allow 
for our various infrastuctures (circleci, heroku) to work in parallel using their own config files
(requirements.txt, avadocs_requirements.txt).
