# app-reference-pagecounter
The repository for page counter repo and re

## repo management ideas
create a repo, empty
- put a TODO and a DONE
- start writing TODO task
- branch / PR per each TODO
- move TODO to done
- all should be clear and nice in the history of the repo

## the task
 for a page couner should be like
- create repo on github
- setup a Vagrantfile that configure the environment, scripts should be idempotent
- when scripts done, create a separate repo for packer-<runtime> and use the same scripts, box should have test, upload box to Vagrant Cloud
- update Vagrantfile to use new box from VagrantCloud
- setup a web page that print zero
- connect app to redis db
- replace zero with redis counter, so it prints 1, 2, 3, etc after visit
  
