Open `fabric-setup.sh` by clicking `HLFADV` > `setup` folder in vscode **Explorer** to view the contents of the bash script. Copy & execute `./fabric-setup.sh`{{copy}} the command to pull down the binaries and images.

#### Validate
You can verify fabric setup was successful by listing contents of the directory is running on Your System by running `cd fabric-samples && ls -la`{{copy}} command.

You can also verify setup was successful by running following commands on your System.
`orderer version`{{copy}}

`peer version`{{copy}}

It will also create Creates the folders under the project root
    - fabric-samples

**Note:** Please wait for the above script to complete, It will take around 3 minutes to complete.