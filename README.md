# lightning-node
Repo for spinning up your own lightning node

Run your docker container by following command:
docker run --name bitcoind_testnet -d -v /PATH:/data -p 18333:18333 -p 18332:18332 YOUR_CONTAINER_NAME:latest
