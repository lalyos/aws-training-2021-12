This repo contains various scripts and templates that are
used during the AWS workshop

## ec2 helper script

This script hepls to list/clean up various aws resources.
During the training we create a couple of resources (instance, instanceTemplates, images, loadbalancers, ...) which has to be deleted. Instead of deleting manually from the console. Use this script.

## ec2 usage

list available commands
```
./ec2
```

to run one of the functions, use the function name prefixed with `::`
```
./ec2 ::list-lbs
```
### debug log

Any command can print debug level messages by:
- appending a `-d` parameter to the end
- setting the `DEBUG` env variable for permanent effect