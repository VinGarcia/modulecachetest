# Module Cache Test

This is an experiment for exploring how easy it is to create an external package
with code that can be installed with go install or go get but that won't appear
on the actual github repo.

So I will first make a hello world main.go and push it, then do a change to that code
and push it again, then forcefully remove that commit from the github master branch.

After that if everything works as I expect when doing a go install or go get the latest
version will be the one that was removed from the repo.
