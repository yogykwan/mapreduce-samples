# mapreduce-samples
Some Mapreduce projects in Java on Mac.

# Deploy

### Docker
1. Download docker.dmg from https://docs.docker.com/docker-for-mac/
2. Run docker from launchpad
3. Set CPU and Memory in Advanced

### Hadoop
```
sudo docker pull joway/hadoop-cluster
git clone https://github.com/joway/hadoop-cluster-docker
sudo docker network create --driver=bridge hadoop

cd hadoop-cluster-docker
sudo ./start-container.sh
./start-hadoop.sh
```

## MAMP
1. Download MAMP.pkg from https://www.mamp.info/en/
2. Run MAMP from launchpad
3. Start Servers
