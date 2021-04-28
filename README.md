# WAGO_Docker_Grafana_Influxdb
Docker on WAGO Controllers. Here is an example how to use e!RUNTIME applications with docker containers: Grafana (port 3000) with Influxdb (ports 8086/8089udp).

# HOW TO
1. Install Docker: https://github.com/WAGO/docker-ipk
2. Add docker-compose: https://github.com/WAGO/docker-compose
3. Copy all files to the controller (using ftp of ssh client)
4. Connect via SSH (www.putty.org) to the controller and run command "docker-compose up -d" in catalog where docker-compose file is.
5. Check http://<controller_ip>:3000
