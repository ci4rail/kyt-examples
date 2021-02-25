# GPS-demo

*Note: this demo is still WIP*

This demo demonstrates the complete stack from the sensor (GPS) on the device to data in the cloud. 

## Usage

Deploy the manifest to your kyt device using

```
# deploy
# Note: kyt login must be performed prior applying manifests
$ kyt alm apply -f gps-demo.yaml

# See events coming in using `az` tool.
# Note: az login must be performed prior monitoring events.
$ az iot hub monitor-events --output table --hub-name <iothub-name>
```