# H1 Example geth.service daemon

This example geth daemon service  using systemctl 
- create config file 
  **#geth dumnconfig > location/config.toml** 
- Edit config file as you need  example was put in /mnt/geth/ whith name config-rikenby.toml 
- enable rpc , ws at localhost 
- you can custom config as example 

how to add : 
1.git clone (https://github.com/sicute/geth.service.git)
2.Edit config-rikenby.toml
3.Copy to folder you want put.
4.put at /etc/systemd/system/ 
  ..*sudo cp geth.service /etc/systemd/system/
5.sudo systemctl enable geth.service 
6. sudo systemctl start geth.service
7.sudo systemctl status geth.service
 

@sonjaya.web.id 
