# ToDo UI Tanzu Build Service demo

Build the ToDo UI demo with Tanzu build service, commit a change to this repo and a new build will be created automatically


## Create the build service image
```
kp image create <name> --tag harbor.tanzuworld.com/<project> --git <git repo> -n <namespace>
```
### Check the build status with:
```
kp build list -n builds <name>
```


