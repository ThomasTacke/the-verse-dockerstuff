# the-verse-dockerstuff

Just a playground for raspberry pi.

## Home Assistant

Mainly a dockerfile with mqtt broker and influxdb for long time storage of sensor values. And a Grafana for additional graphs.

Fill out the `.env.example` with good values and rename it to `.env`. Run `docker-compose up -d` to start all services.

Have Fun!

## PiHole

More or less the docker-compose example from the PiHole page with DHCP enable since it is used as DHCP-Server for the network as well.

Fill out the `.env.example` with good values and rename it to `.env`. Run `docker-compose up -d` to start all services.

Have Fun!
