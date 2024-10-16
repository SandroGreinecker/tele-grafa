# 

Telegraf config for cpu and gpu usage
## Installation

install telegraf

```bash
#download telegraf
$ wget https://dl.influxdata.com/telegraf/releases telegraf-1.32.1_windows_amd64.zip -UseBasicParsing -OutFile telegraf-1.32.1_windows_amd64.zip

#expand archive
$ Expand-Archive .\telegraf-1.32.1_windows_amd64.zip -DestinationPath 'C:\path'

# Install service
telegraf.exe --service install --config "C:\path-to-conf-file"

#run service
net start telegraf

#check if service is running
sc query telegraf

# stop service
$ net stop telegraf

#uninstall service
$ telegraf.exe --service uninstall
```
