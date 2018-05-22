Dicoogle IPFS Storage Plugin 
========================

This is a Dicoogle plugin to support the storage of files over IPFS. 

Getting Started
---------------

### Installing and running Dicoogle

1. Go to http://www.dicoogle.com/?page_id=67
2. Download version 2 (or later) of Dicoogle
3. Extract your contents to its own directory (e.g. "~/dicoogle" or "C:\dicoogle", depending on the platform).
4. Run Dicoogle with: sh Dicoogle.sh (OSX / Linux) or Dicoogle.bat (Windows).
5. You should see your web browser opening the Dicoogle user interface. Is it running? You're ok!


### Run IPFS Daemon 


$ ./ipfs init

$ ./ipfs daemon


```
Initializing daemon...
Swarm listening on /ip4/127.0.0.1/tcp/4001
Swarm listening on /ip4/169.254.195.127/tcp/4001
Swarm listening on /ip4/172.20.20.25/tcp/4001
Swarm listening on /ip4/192.168.1.72/tcp/4001
Swarm listening on /ip6/::1/tcp/4001
Swarm listening on /p2p-circuit/ipfs/QmPYwyhd9WfH6cmyXh4SJpSkxweeHmUbohao6g4H4zhD3G
Swarm announcing /ip4/127.0.0.1/tcp/4001
Swarm announcing /ip4/169.254.195.127/tcp/4001
Swarm announcing /ip4/172.20.20.25/tcp/4001
Swarm announcing /ip4/192.168.1.72/tcp/4001
Swarm announcing /ip4/2.83.194.251/tcp/60663
Swarm announcing /ip6/::1/tcp/4001
API server listening on /ip4/127.0.0.1/tcp/5001
Gateway (readonly) server listening on /ip4/127.0.0.1/tcp/8080
Daemon is ready
``` 


### Downloading and building the plugin

Maven is required in order to build the project. An IDE with Maven support such as Netbeans may also help.

1. Clone the git repository at https://github.com/bioinformatics-ua/dicooglePluginSample.git

2. Go to the project's base directory in a command line and run `mvn install`. Alternatively, open
   the Maven project of the plugin with your IDE, then force it to build your project.

3. If the building task is successful, you will have a new jar with dependencies in the target
   folder (target/dicoogle-plugin-sample-2.0-jar-with-dependencies.jar).


### Using your plugin

1. Copy your plugin's package with dependencies (target/dicoogle-plugin-sample-2.0-jar-with-dependencies.jar)
   to the "Plugins" folder inside the root folder of Dicoogle.

2. Run Dicoogle. The plugin will be automatically included.


Web service plugin : 
--------------------------------------

To test the webservice plugin, you may open your browser and navigate to these URLs:


### Use case

1) Store medical imaging over IPFS
2) Failures
3) Avoid changes in medical imaging 
4) Allow tracebility 


## Support and consulting
[<img src="https://raw.githubusercontent.com/wiki/BMDSoftware/dicoogle/images/bmd.png" height="64" alt="BMD Software">](https://www.bmd-software.com)

Please contact [BMD Software](https://www.bmd-software.com) for professional support and consulting services.



Platforms
----------

Dicoogle IPFS has been tested in:

- Windows
- Linux
- Mac OS X
- FreeBSD and OpenBSD

For more information, please visit http://www.dicoogle.com

