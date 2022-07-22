# PostgSail
Effortless cloud based solution for storing and sharing your SignalK data. Allow to effortlessly log your sails and monitor your boat. 

## Featutes
- Automatically log your voyages without manually starting or stopping a trip.
- Automatically capture the details of your voyages (boat speed, heading, wind speed, etc)
- Timelapse video your trips!
- Add custom notes to your logs.
- Export to CSV or GPX and download your logs.
- Aggregate your trip statistics: Longest voyage, time spent at anchorages, home ports etc.
- See your moorages on a global map, with incoming and outgoing voyages from each trip.
- Monitor your boat (position, depth, wind, temperature, battery charge status, etc.) remotely
- Notification via email or PushOver.

## SQL
It is all about SQL.

### Dependencies

`docker-compose` is used to start environment dependencies. Dependencies consist of 2 containers:

- `timescaledb-postgis` (PostgreSQL with TimescaleDB extension along with the PostGIS extension.)
- `postgrest` (Standalone web server that turns your PostgreSQL database directly into a RESTful API.)

### Optional docker images
- Grafana, visualize and monitor your data
- pgadmin, web UI to monitor and manage multiple PostgreSQL
- swagger, web UI to visualize documentation from PostgREST

### Software reference
Out of the box iot platform using docker with the following software:
- [Signal K server, a Free and Open Source universal marine data exchange format](https://signalk.org)
- [PostgreSQL, open source object-relational database system](https://postgresql.org)
- [TimescaleDB, Time-series data extends PostgreSQL](https://www.timescale.com)
- [PostGIS, a spatial database extender for PostgreSQL object-relational database.](https://postgis.net/)
- [Grafana, open observability platform | Grafana Labs](https://grafana.com)
