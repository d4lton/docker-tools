# docker-tools
Docker tools

## Service Exec

Execute a command on the given service container in the given stack. If the command isn't specified, `/bin/bash` will be executed.

This utility should be run from one of the nodes in the Docker Swarm.

`usage: service-exec <stack-name> <service-name>.<service-index> [command]`

Example:

`$ service-exec my-stack my-service.1`
