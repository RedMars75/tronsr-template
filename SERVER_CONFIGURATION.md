Describe your server configuration
I will start with AWS hosting for flexibility. I would then move to either physical hardware or to a local cloud provider. I will start with an AWS server and expand as needed.

Ideally, I want to have several nodes including

Testnet node – m5.xlarge
Mainnet nodes to have 2 or 3 nodes.
Mainnet additional nodes will be backup nodes ready to take over from primary node or to work in cluster mode. Busy looking at failover options and will implement the best possible option.
Mainnet nodes will comply with Tron recommendation of AWS x1.16xlarge.
Server placement is AWS United States West (CA)
Server configuration for Mainnet Node is x1.16xlarge 64 core 1T memory 20T SSD storage (EBS) 25G bandwidth
