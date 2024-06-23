softether-vpn-server
```shell
sudo docker run -itd --name softether-vpn-server --privileged --network=host --cap-add NET_ADMIN -v /opt/vpnserver/:/mnt --restart=always softethervpn/vpnserver:stable
```
