## Persist Grafana data using StatefulSet

Provision a Grafana server using a StatefulSet with 2GB volume to persist the server's data and configurations. All Grafana data is stored under /var/lib/grafana.

The server should run using 1 replica, Making sure the StatefulSet was created successfully, and that Grafana data is persistent.
