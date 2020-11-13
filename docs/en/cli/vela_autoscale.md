## vela autoscale

Attach autoscale trait to an app

### Synopsis

Attach autoscale trait to an app

```
vela autoscale <appname> [args]
```

### Examples

```
vela autoscale frontend
```

### Options

```
      --cpuPercent int   specify the value for CPU utilization, like 80, which means 80%
      --detach           detach trait from service
  -h, --help             help for autoscale
      --max int          maximal replicas of the workload
      --min int          minimal replicas of the workload
  -s, --staging          only save changes locally without real update application
      --svc string       specify one service belonging to the application
```

### Options inherited from parent commands

```
  -e, --env string   specify environment name for application
```

### SEE ALSO

* [vela](vela.md)	 - 

###### Auto generated by spf13/cobra on 12-Nov-2020