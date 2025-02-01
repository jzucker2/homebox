# homebox

Need to create a file at `/etc/environment` containing the followinfg for health checks:

```
# Could also use America/New_York or America/Chicago or America/Denver
TZ=America/Los_Angeles
# The HOMEBOX_DHCP_IP should be whatever your ethernet port is
HOMEBOX_DHCP_IP=10.0.1.101
ZIGBEE_USB_DONGLE_PORT=/dev/serial/by-id/usb-ITead_Sonoff_Zigbee_3.0_USB_Dongle_Plus_fcdb20559e9ced11a9aa77faa7669f5d-if00-port0
DOCKER_LOCALHOST="host.docker.internal"
MUSIC_ASSISTANT_EXTERNAL_PORT=8095
CADVISOR_EXTERNAL_PORT=8080
NODE_EXPORTER_EXTERNAL_PORT=9100
PROMTAIL_EXTERNAL_PORT=9080
```
