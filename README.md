# homebox

This is for running a Music Assistant box agnostic of most other things.

Need to create a file at `/etc/environment` containing the followinfg for health checks:

```
# Could also use America/New_York or America/Chicago or America/Denver
TZ=America/Los_Angeles
# The HOMEBOX_DHCP_IP should be whatever your ethernet port is
HOMEBOX_DHCP_IP=10.0.1.101
DOCKER_LOCALHOST="host.docker.internal"
MUSIC_ASSISTANT_EXTERNAL_PORT=8095
CADVISOR_EXTERNAL_PORT=8080
NODE_EXPORTER_EXTERNAL_PORT=9100
PROMTAIL_EXTERNAL_PORT=9080
```
