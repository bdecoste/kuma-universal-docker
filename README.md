# kuma-universal-docker
./kong-mesh-1.3.3/bin/kumactl install transparent-proxy --skip-resolv-conf --redirect-all-dns-traffic  --redirect-outbound-port 15001 --redirect-inbound=true --redirect-inbound-port 15006 --redirect-inbound-port-v6 15010 —redirect-dns-upstream-target-chain DOCKER_OUTPUT --kuma-dp-user kuma-dp
