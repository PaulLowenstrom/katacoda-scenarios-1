

Run `cat fabric-setup.sh`{{execute T1}} to view the contents of the bash script. Copy & execute `./fabric-setup.sh`{{copy}} the command to download and install peer CLI.

#### Validate
You can verify peer is installed on your System by running `peer --version`{{copy}} command.

#### Usage
Here’s some examples using the different available flags on the peer command `peer --help`{{copy}}

```
Usage:
  peer [command]

Available Commands:
  chaincode   Operate a chaincode: install|instantiate|invoke|package|query|signpackage|upgrade|list.
  channel     Operate a channel: create|fetch|join|list|update|signconfigtx|getinfo.
  help        Help about any command
  logging     Logging configuration: getlevel|setlevel|getlogspec|setlogspec|revertlevels.
  node        Operate a peer node: start|status|reset|rollback.
  version     Print fabric peer version.
```
