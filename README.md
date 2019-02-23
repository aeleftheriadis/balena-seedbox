# balena-transmission-openvpn

Deploy [haugene/docker-transmission-openvpn](https://github.com/haugene/docker-transmission-openvpn) project on Balena devices.

## Usage

### Deploy
```bash
balena push {balena_project}
```

### Configure

Go to your Balena dashboard, Service Variables and add your custom configuration variables.

Transmission Web UI will be available after enabling `PUBLIC DEVICE URL` on your Balena Device dashboard.
