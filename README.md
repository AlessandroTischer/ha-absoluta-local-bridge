# ha-absoluta-local-bridge

A native Home Assistant OS app that integrates your **Bentel Absoluta** alarm panel directly into Home Assistant, with no Docker or external setup required.

This app wraps the [bentel-absoluta-local](https://github.com/Shikaban/bentel-absoluta-local) Java bridge and connects your panel to the built-in Mosquitto broker via the ITv2 protocol over your local network.

---

## Installation

1. Open Home Assistant and navigate to **Settings → Apps → App Store**
2. Click the three-dot menu and select **Repositories**
3. Add this URL: `https://github.com/AlessandroTischer/ha-absoluta-local-bridge`
4. Find **Bentel Absoluta Local Bridge** in the store and click **Install**

---

## Configuration

| Option | Description |
|---|---|
| `alarm_address` | IP address of the Bentel Absoluta panel |
| `alarm_port` | TCP port of the panel (default: `3064`) |
| `alarm_pin` | PIN code for the panel |
| `mqtt_address` | MQTT broker address |
| `mqtt_port` | MQTT broker port (default: `1883`) |
| `mqtt_username` | MQTT username |
| `mqtt_password` | MQTT password |

---

## Documentation

For full documentation, MQTT topic reference, Home Assistant dashboard templates, and troubleshooting, see the main project repository:

**[bentel-absoluta-local](https://github.com/Shikaban/bentel-absoluta-local)**

---

## Disclaimer

This project is not affiliated with or endorsed by Bentel Security s.r.l.

This software is provided "as is", without any warranty of any kind. Use it at your own risk.
