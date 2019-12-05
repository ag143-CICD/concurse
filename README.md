# concurse

Setup and usage of Concurse

Setup
https://concourse-ci.org/index.html

or

prerequisite install docker

open powershell(windows) or terminal(MACOS or linux)
$ wget https://concourse-ci.org/docker-compose.yml
$ docker-compose up -d
Creating docs_concourse-db_1 ...
Creating docs_concourse-db_1 ... done
Creating docs_concourse_1 ...
Creating docs_concourse_1 ... done


Concourse will be running at localhost:8080. You can log in with the username/password as test/test.

Next, install fly CLI by downloading it from the web UI and target your local Concourse as the test user:

$ fly -t tutorial login -c http://localhost:8080 -u test -p test
logging in to team 'main'

target saved

Kick start here

https://concoursetutorial.com/basics/task-hello-world/

