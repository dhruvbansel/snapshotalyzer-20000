# snapshotalyzer-20000
Demo project to manage AWS EC2 instances

##About

This project is a demo and uses AWS boto3 to manage instance snapshots.

##Configuring

shotty uses the configuration file created by the AWS cli e.g.

"aws configure --profile shotty"

##Running

"pipenv run "python shotty/shotty.py <command> <sub-commmand> <--project = PROJECT>""

*command* is instances, volumes and Snapshots
*sub -command* is list, start and stop [depends on command]
*project* is optional; --project = Valkyrie
