
e3-eget  
======
ESS Site-specific EPICS module : eget


In case one would like to use V4 commands (pvgetx, pvputx, and eget) with EPICS base 3.15.X, because of
no pvAccess utility commands with e3. 

```
$ make init
$ make patch
$ make build
$ make install
```


The following executable files are in $(EPICS_BASE)/bin/$(EPICS_HOST_ARCH)/

```
pvgetx
pvputx
eget
```

