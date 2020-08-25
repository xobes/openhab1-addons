# MQTT Actions

Publish a message to a topic on an MQTT broker.

## Prerequisites

In addition to the MQTT Action service, the [MQTT binding (1.x)](https://www.openhab.org/addons/bindings/mqtt/) must be installed and configured.  The action can reference the broker(s) that are configured for the MQTT binding.

## Action

- `publish(String brokerName, String topic, String message)`: Publish the message to topic using the specified MQTT broker.
