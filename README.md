# evioPlugin
CNI plugin for EdgeVPN - Enhanced version of bridge plugin to work with OVS and utility to allocate IP address range 
to nodes and generate config file for the plugin.
Dependency on github.com/containernetworking tag v0.7.5  
``` 
mkdir -p $GOPATH/github.com/containernetworking
cd $GOPATH/github.com/containernetworking
git clone https://github.com/containernetworking/plugins.git
cd plugins
git checkout tags/v0.7.5
cd plugins/main/
git clone https://github.com/saumitraaditya/evioPlugin.git
```
