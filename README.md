# snapshotalyzer-30000
Demo project to ,mamage AWS EC2 instances 

## About
This project is a demo, and used boto3 to manage AWS EC2 instance snapshots.

##Configuring

shotty uses the configuration file created by AWS cli e.g.

'aws configure -- profile shotty'

## Running
'pipenv run python snapshotalyzer-30000/shotty.py <command> <subcommand> <--project=PROJECT>'

*command* is instances, volumnes, or snapshots
*subcommand* depends on command
*project* is optional


