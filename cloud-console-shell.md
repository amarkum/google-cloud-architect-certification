## Create Shell Configuration

### Create the Shell Config file
```shell
vi infraclass/config
```

```shell
INFRACLASS_REGION=us-central-1
INFRACLASS_PROJECTID=<PROJECT_ID>
```

### Open the profile
```shell
$ vi .profile
```

### Add `infraclass/config` to `.profile`
```shell
source infraclass/config
```
