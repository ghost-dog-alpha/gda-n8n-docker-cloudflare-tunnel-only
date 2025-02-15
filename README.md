# gda-n8n-docker-cloudflare-tunnel-only

You may need to increase these values if you get errors from the tunnel.

sudo sysctl -w net.core.rmem_default=26214400
sudo sysctl -w net.core.wmem_default=26214400
sudo sysctl -w net.core.rmem_max=26214400
sudo sysctl -w net.core.wmem_max=26214400