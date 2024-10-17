# 

Telegraf config for cpu and gpu usage
## Installation

install telegraf

```bash
#download telegraf
wget https://dl.influxdata.com/telegraf/releases/telegraf-1.32.1_windows_amd64.zip -UseBasicParsing -OutFile telegraf-1.32.1_windows_amd64.zip

#expand archive
Expand-Archive .\telegraf-1.32.1_windows_amd64.zip -DestinationPath 'C:\path'

#run config
.\telegraf.exe --config .\config.conf