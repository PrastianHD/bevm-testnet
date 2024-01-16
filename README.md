## bevm-testnet

Download the installation shell of docker officially

```
curl -fsSL https://get.docker.com -o get-docker.sh
```

```
sudo sh get-docker.sh
```

```
cd /var/lib
```

```
sudo docker pull btclayer2/bevm:v0.1.1
```

Set "your_node_name" as the BEVM address.
```
sudo docker run -d -v /var/lib/node_bevm_test_storage:/root/.local/share/bevm btclayer2/bevm:v0.1.1 bevm "--chain=testnet" "--name=your_node_name" "--pruning=archive" --telemetry-url "wss://telemetry.bevm.io/submit 0"
```

```
docker ps
```

```
docker ps
```

```
docker logs -f YOUR-CONTAINER-ID
```

OPTIONAL !!

```
docker restart YOUR-CONTAINER-ID
```

```
docker stop YOUR-CONTAINER-ID
```

```
docker remove YOUR-CONTAINER-ID
```
