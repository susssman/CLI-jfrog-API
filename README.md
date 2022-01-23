# CLI-jfrog-API
Project for Jfrog API
made by Itay Rotman
cli-jfrog - a CLI for Jfrog API with few commands

Commands:
ping, version, create-user, delete-user, storage-info, create-repo, update-repo, get-repo.
execute: ./cli-jfrog help
for more info.

Usage:
./cli-jfrog <command>

if there is config file
-YES
--check if there is token
---YES
----execute command
---NO
----Enter username and password to generate a token for an hour.
-----Executes command
-NO
--Creates new config file
---Asks for servername
----Enter username and password to generate a token for an hour.
-----Executes command.
