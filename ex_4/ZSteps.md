# Attack description
- We want to connect to the VM using SSH and the public IP.
- We used basic ssh command like this to trigger the alert :
```shell
ssh randomuser@VM
```

(SentinelIncidentsDetection)
We scan the syslog messages to handle cases like:
- User exist
- User does not exist, but still a connection