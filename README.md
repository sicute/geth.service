# geth.service
This example geth daemon service  using systemctl 
- create config file 
  # geth dumnconfig > location/config.toml 
- Edit config file as you need  example was put in /mnt/geth/ whith name config-rikenby.toml 
- enable rpc , ws at localhost 
- you can custom config as example 

how to add : 
- git clone https://github.com/sicute/geth.service.git
- put at /etc/systemd/system/ 
  sudo cp geth.service /etc/systemd/system/
- sudo systemctl enable geth.service 
- sudo systemctl start geth.service
- sudo systemctl status geth.service
 

@sonjaya.web.id 
