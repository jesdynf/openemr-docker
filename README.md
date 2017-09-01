# OpenEMR Docker

## AWS LightSail

https://davekz.com/docker-on-lightsail/

Base OS, "Ubuntu 16.04", paste, go
```
curl -L https://raw.githubusercontent.com/jesdynf/openemr-docker/master/lightsail-launch.sh > lightsail-launch.sh
chmod +x lightsail-launch.sh
sudo ./lightsail-launch.sh
```

openemr config: do not create db, mysql server 'mysql', creds "root/root"
