

Sonaric is an AI-powered network that revolutionizes the way blockchain nodes are operated and managed. Unlike traditional DePINs or compute marketplaces, Sonaric enables node operators to run blockchain nodes on their own hardware, driven by their own interests and incentives.

### Update :
```
sudo apt update && sudo apt upgrade
```

### Install Sonaric

```
wget https://raw.githubusercontent.com/Winnode/Sonaric-AI-Node/main/linux-install-sonaric.sh
```
```
chmod +x linux-install-sonaric.sh
```
```
./linux-install-sonaric.sh
```
```
apt upgrade sonaric
```

### Node info

```
sonaric node-info
```

```
ssh -L 127.0.0.1:44003:127.0.0.1:44003 -L 127.0.0.1:44004:127.0.0.1:44004 -L 127.0.0.1:44005:127.0.0.1:44005 -L 127.0.0.1:44006:127.0.0.1:44006 root@<ip_vps>
```

### Change Name your Node

```
sonaric identity-export -o YourNode.identity
sonaric identity-import -i YourNode.identity
systemctl status sonaricd
sonaric node-rename furinode
```

### Save YourNode Identity

```
cat  Winnode.identity
```

### Check Point

```
sonaric points
```

### Check your Node here 

https://tracker.sonaric.xyz/
