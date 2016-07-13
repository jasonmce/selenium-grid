To create the safe network:
bash create_safe_network.sh

To start fresh:
docker-compose up -d

To add/scale services:
docker-compose scale firefox=4
docker-compose scale chrome=5
docker-compose scale firefox=1 chrome=1

To destroy and clean up:
docker-compose down

