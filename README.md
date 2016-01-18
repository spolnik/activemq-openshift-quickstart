The OpenShift `diy` cartridge documentation can be found at:

https://github.com/openshift/origin-server/tree/master/cartridges/openshift-origin-cartridge-diy/README.md

to quick create app use the following command :
```
rhc app-create activemq diy --from-code=git://github.com/spolnik/activemq-openshift-quickstart.git
```

If you would like to run activemq web console, firstly you need to do ports forwarding :
```
rhc port-forward activemq
```
