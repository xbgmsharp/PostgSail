# PostgSail
Effortless cloud based solution for storing and sharing your SignalK data. Allow to effortlessly log your sails. 

### Dependencies

`docker-compose` is used to start environment dependencies. Dependencies consist of 2 containers:

- `timescaledb-postgis` (PostgreSQL with TimescaleDB extension along with the PostGIS extension.)
- `postgrest` (Standalone web server that turns your PostgreSQL database directly into a RESTful API.)

### Optional

- Grafana, visualize nad monitor your data
- pgadmin, web UI to monitor and manage multiple PostgreSQL
- swagger, web UI to visualize documentation from PostgREST
