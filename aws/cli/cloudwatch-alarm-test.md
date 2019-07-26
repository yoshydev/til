# AWS CLI
## CloudWatchのアラームをテストする

AWS CLIからテストが可能

`$ aws cloudwatch set-alarm-state --alarm-name "{alarm_name}" --state-value ALARM --state-reason "{reason_text}" --profile {profile_name}`
