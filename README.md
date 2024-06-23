softether-vpn-server
```
sudo docker run -itd --name softether-vpn-server --privileged \
--network=host --cap-add NET_ADMIN -v /opt/vpnserver/:/mnt --restart=always \
softethervpn/vpnserver:stable
```

portainer-ce
```
docker run -d -p 9000:9000 -p 9443:9443 --name portainer \
--restart=always \
-v /var/run/docker.sock:/var/run/docker.sock \
-v portainer_data:/data \
portainer/portainer-ce
```
