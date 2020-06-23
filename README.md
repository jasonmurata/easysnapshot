# easysnapshot
Tool to make snapshots simpler

## About

This is a lab to use boto3 to manage EC2 instance snapshots

## Config
easyss uses the config file create by the AWS cli eg:
`aws configure --profile easysnapshot`

## Running

pipenv run python easyss/easyss.py <command> <subcommand> <--project=PROJECT>

*command* is instances, volumes, or snapshots
*subcommand* - depends on command 
*project* is optional



