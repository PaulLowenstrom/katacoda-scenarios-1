You can use the Azure CLI to stream Java stdout and stderr logging, as well as other application logging.

Here's how to configure your function app to write application logging by using the Azure CLI:

Azure CLI

`

Try It
az webapp log config --name functionname --resource-group myResourceGroup --application-logging true
To stream logging output for your function app by using the Azure CLI, open a new command prompt, Bash, or Terminal session, and enter the following command:

Azure CLI

`

Try It
az webapp log tail --name webappname --resource-group myResourceGroup
The az webapp log tail command has options to filter output by using the --provider option.

To download the log files as a single ZIP file by using the Azure CLI, open a new command prompt, Bash, or Terminal session, and enter the following command:

Azure CLI

`

Try It
az webapp log download --resource-group resourcegroupname --name functionappname
You must have enabled file system logging in the Azure portal or the Azure CLI before running this command.