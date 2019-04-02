
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

With EPICS base 7.0.1.1, please ignore `make patch` so

```
$ make init
$ make build
$ make install
```


The following executable files are in $(EPICS_BASE)/bin/$(EPICS_HOST_ARCH)/

```
pvgetx
pvputx
eget
```

