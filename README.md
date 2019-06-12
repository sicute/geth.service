# geth.service
This example geth daemon service  using systemctl 
- config file was put in /mnt/geth/ whith name config-rikenby.toml 
- enable rpc , ws at localhost 
- you can custom config as example 

how to add : 
- clone 
- put at /etc/systemd/system/ 
  sudo cp geth.service /etc/systemd/system/
- sudo systemctl enable geth.service 
- sudo systemctl start geth.service
- sudo systemctl status geth.service
 
