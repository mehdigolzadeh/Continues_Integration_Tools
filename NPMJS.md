# The process of creating NPM dataset

Out of 1601989 packages available in NPM package registry (https://replicate.npmjs.com/_all_docs). 
I randomly selected 300000 package_id and started to download their coressponding information including:

Name: the package name
Created: time of the creation
Updated: last update time recorded for the package
Maintainers_name: name of the maintainer
Maintainers_email: email address of the maintainer
Homepage: home page
Repository: repository address of the package
Author: author name
License: license type

Since the initial list only contains ID and a hashcode to retrive the repository address I need to call another npmjs endpoint (https://replicate.npmjs.com/{packagename}) for each package ID and I decided to store other retrieved information as well.

Then I filtered out all packages with either empty repository address feild, repository address other than github or invalid addresses.
This led to a list with xxxx packages,


